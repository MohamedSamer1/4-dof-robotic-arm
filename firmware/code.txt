#include <Adafruit_PWMServoDriver.h>
#include <Wire.h>

Adafruit_PWMServoDriver pwm = Adafruit_PWMServoDriver();

#define SERVOMIN 150
#define SERVOMAX 600

int angleToPulse(int angle) { return map(angle, 0, 180, SERVOMIN, SERVOMAX); }

// positions
#define MAIN_HOME 0
#define MAIN_PICK 60

#define ARM_UP 45
#define ARM_DOWN 90

#define CLAMP_CLOSE 0
#define CLAMP_OPEN 90

void moveServoSmooth(int channel, int startAngle, int endAngle, int stepDelay) {
  if (startAngle <= endAngle) {
    for (int a = startAngle; a <= endAngle; a++) {
      pwm.setPWM(channel, 0, angleToPulse(a));
      delay(stepDelay);
    }
  } else {
    for (int a = startAngle; a >= endAngle; a--) {
      pwm.setPWM(channel, 0, angleToPulse(a));
      delay(stepDelay);
    }
  }
}

void setup() {
  pwm.begin();
  pwm.setPWMFreq(50);
  delay(1000);

  // initial state
  pwm.setPWM(0, 0, angleToPulse(MAIN_HOME));
  pwm.setPWM(1, 0, angleToPulse(ARM_UP));
  pwm.setPWM(2, 0, angleToPulse(ARM_UP));
  pwm.setPWM(3, 0, angleToPulse(CLAMP_CLOSE));

  delay(2000);
}

void loop() {
  // 1. rotate to object (smooth)
  moveServoSmooth(0, MAIN_HOME, MAIN_PICK, 15);

  // 2. clamp open
  moveServoSmooth(3, CLAMP_CLOSE, CLAMP_OPEN, 10);

  // 3. arms go down (smooth both)
  moveServoSmooth(1, ARM_UP, ARM_DOWN, 15);
  moveServoSmooth(2, ARM_UP, ARM_DOWN, 15);

  // 4. clamp close
  moveServoSmooth(3, CLAMP_OPEN, CLAMP_CLOSE, 10);

  // 5. lift arms
  moveServoSmooth(1, ARM_DOWN, ARM_UP, 15);
  moveServoSmooth(2, ARM_DOWN, ARM_UP, 15);

  // 6. return home
  moveServoSmooth(0, MAIN_PICK, MAIN_HOME, 15);

  // 7. open clamp
  moveServoSmooth(3, CLAMP_CLOSE, CLAMP_OPEN, 10);
}