<p align="center">
    <img src="images/hero-banner.png" alt="4-DOF Robotic Arm with Mechanical Gripper" width="100%">
</p>

<h1 align="center">🦾 4-DOF Robotic Arm with Mechanical Gripper</h1>

<p align="center">
A servo-actuated robotic manipulator engineered through a complete workflow involving
mechanical design, CAD modeling, embedded programming, kinematic analysis,
electronics integration, and prototype development.
</p>

<p align="center">

<img src="https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white">
<img src="https://img.shields.io/badge/Autodesk%20Inventor-E34F26?style=for-the-badge&logo=autodesk&logoColor=white">
<img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white">
<img src="https://img.shields.io/badge/Robotics-1F2937?style=for-the-badge">
<img src="https://img.shields.io/badge/Kinematics-2563EB?style=for-the-badge">
<img src="https://img.shields.io/badge/Servo%20Control-0EA5E9?style=for-the-badge">

</p>

---

# 📑 Table of Contents

- [📖 Project Overview](#-project-overview)
- [🎯 Design Objectives](#-design-objectives)
- [📋 Technical Specifications](#-technical-specifications)
- [🏗️ System Architecture](#️-system-architecture)
- [⚙️ Mechanical Design](#️-mechanical-design)
- [📐 Kinematic Analysis](#-kinematic-analysis)
- [🔌 Electronics Design](#-electronics-design)
- [🧠 Control System](#-control-system)
- [💻 Software Implementation](#-software-implementation)
- [🖼️ CAD Gallery](#️-cad-gallery)
- [🤖 Prototype](#-prototype)
- [📊 Results](#-results)
- [🚧 Challenges](#-challenges)
- [🚀 Future Improvements](#-future-improvements)
- [📁 Repository Structure](#-repository-structure)
- [📄 Documentation](#-documentation)
- [👥 Team](#-team)
- [📄 License](#-license)

---

# 📖 Project Overview

## Background

Robotic manipulators are fundamental components in modern automation, enabling precise and repeatable motion in applications ranging from manufacturing and assembly to laboratory automation and education. Designing a robotic arm requires the integration of mechanical engineering, electronics, embedded systems, and motion control into a single coordinated system.

This project presents the development of a **4-Degree-of-Freedom (4-DOF) robotic arm equipped with a servo-driven mechanical gripper**, designed to perform basic pick-and-place operations while demonstrating the principles of robotic manipulation.

Unlike a simple hobby build, the project follows a structured engineering workflow that includes concept development, CAD modeling, electronics integration, embedded programming, and physical prototype validation.

---

## Project Goals

The objective of this project was to design and build a compact robotic manipulator capable of controlled object handling while applying fundamental concepts of mechatronics engineering.

The project focuses on:

- Mechanical system design
- CAD modeling and assembly
- Servo motor actuation
- Embedded programming with Arduino
- Robotic kinematics
- Electronics integration
- Motion control
- Prototype development

---

## Key Features

- 🦾 Four Degrees of Freedom (4-DOF)
- 🤏 Servo-Driven Mechanical Gripper
- 🎯 Pick-and-Place Functionality
- ⚙️ Arduino-Based Motion Control
- 📐 Fully Designed in Autodesk Inventor
- 🔩 Modular Mechanical Assembly
- 📊 Kinematic Motion Analysis
- 🔌 Integrated Electronic System
- 📦 Compact Educational Robotics Platform

---

# 🎯 Design Objectives

The project was developed to satisfy the following engineering objectives:

- Design a compact robotic manipulator with four rotational joints.
- Develop a reliable mechanical gripper capable of object manipulation.
- Achieve smooth and accurate servo-controlled motion.
- Create a modular CAD assembly for simplified manufacturing and maintenance.
- Integrate embedded hardware and software into a complete mechatronic system.
- Demonstrate the fundamentals of robotic manipulation through prototype testing.

---

# 📋 Technical Specifications

| Feature | Specification |
|----------|--------------|
| Degrees of Freedom | 4 |
| End Effector | Mechanical Gripper |
| Actuation | Servo Motors |
| Controller | Arduino Uno |
| Programming Language | C++ |
| CAD Software | Autodesk Inventor |
| Control Method | Joint Position Control |
| Application | Pick-and-Place Operations |

---

# 🏗️ System Architecture

The robotic arm consists of four integrated engineering subsystems that work together to perform controlled manipulation tasks.

```text
                 User Input
                      │
                      ▼
              Arduino Controller
                      │
          ┌───────────┴───────────┐
          ▼                       ▼
     Servo Control         Motion Commands
          │
          ▼
      Servo Motors
          │
          ▼
     Robotic Arm Joints
          │
          ▼
 Mechanical Gripper
          │
          ▼
 Object Manipulation
```

---

## Mechanical Subsystem

- Base Assembly
- Rotating Joints
- Structural Links
- Mechanical Gripper
- Fastening Hardware

---

## Electronics Subsystem

- Arduino Uno
- Servo Motors
- External Power Supply
- Wiring Harness

---

## Software Subsystem

- Arduino Firmware
- Servo Motion Control
- Position Commands
- Sequential Motion Logic

---

<p align="center">
<img src="images/colored-cad-arm.png" width="90%">
</p>

> **Figure 1.** CAD model of the complete 4-DOF robotic arm assembly designed in Autodesk Inventor.

---

> **Engineering Focus**
>
> This project demonstrates how mechanical design, embedded systems, electronics, and robotics can be integrated into a complete mechatronic system. The emphasis is not only on achieving functional motion but also on understanding the engineering principles behind manipulator design, system integration, and controlled robotic movement.
# ⚙️ Mechanical Design

## Design Philosophy

The robotic arm was designed with the objective of creating a compact, lightweight, and modular manipulator capable of performing basic pick-and-place operations while demonstrating the principles of robotic motion and mechatronic system integration.

Throughout the design process, emphasis was placed on balancing structural rigidity, ease of assembly, and smooth joint movement. Every component was modeled in **Autodesk Inventor** before manufacturing to verify dimensions, clearances, and overall system compatibility.

---

## Overall Structure

The manipulator consists of four rotational joints connected through rigid structural links, providing four degrees of freedom for positioning the end effector within its workspace.

The complete mechanical assembly includes:

- Base assembly
- Shoulder joint
- Elbow joint
- Wrist joint
- Mechanical gripper
- Structural links
- Fasteners and servo mounts

<p align="center">
<img src="images/cad-arm.png" width="90%">
</p>

> **Figure 2.** CAD model of the robotic arm assembly.

---

## Modular Design

A modular approach was adopted throughout the design to simplify manufacturing, maintenance, and future upgrades.

Each link and joint can be removed or replaced independently without requiring a complete redesign of the manipulator.

This approach also allows:

- Easier maintenance
- Simplified assembly
- Reduced manufacturing complexity
- Future component upgrades

---

## End Effector

The robotic arm utilizes a servo-actuated mechanical gripper as its end effector.

The gripper converts the rotational motion of a servo motor into the opening and closing movement required to grasp objects securely.

The design allows the arm to manipulate lightweight objects while maintaining a compact overall structure.

---

## Mechanical Design Highlights

- Compact desktop-sized manipulator
- Lightweight structural design
- Modular mechanical assembly
- Servo-integrated joints
- Replaceable mechanical components
- CAD-first engineering workflow

---

# 📐 Kinematic Analysis

## Degrees of Freedom

The robotic arm provides **four degrees of freedom (4-DOF)** through four independently actuated revolute joints.

Each joint contributes to the overall positioning of the end effector within the robot's workspace.

The available motion includes:

- Base rotation
- Shoulder rotation
- Elbow rotation
- Wrist rotation

Together, these joints allow the robotic arm to reach different positions and orientations necessary for basic manipulation tasks.

---

## Joint Configuration

<p align="center">
<img src="images/Screenshot_2026-06-27_000514.png" width="85%">
</p>

> **Figure 3.** Joint arrangement of the robotic arm.

---

## Workspace

The manipulator was designed to maximize the usable workspace while maintaining a compact footprint.

The arrangement of the arm links enables:

- Horizontal positioning
- Vertical positioning
- Object pickup
- Object placement
- Controlled reach within the operating envelope

Although the robot is intended primarily as an educational platform, the same kinematic principles are applied in industrial robotic manipulators.

---

## Motion Control

Each servo motor controls one revolute joint independently.

Coordinated movement of all four joints allows the end effector to follow smooth motion paths between target positions.

Joint angles are generated by the Arduino controller and transmitted directly to the corresponding servo motors.

---

# 🔌 Electronics Design

The robotic arm is controlled by an Arduino-based embedded system responsible for coordinating the motion of all servo motors.

The electrical system was designed with simplicity, reliability, and ease of implementation in mind.

---

## Hardware Components

- Arduino Uno
- Servo Motors
- External Power Supply
- Wiring Harness
- Mechanical Gripper Servo

---

## Wiring Diagram

<p align="center">
<img src="images/wiring.jpeg" width="85%">
</p>

> **Figure 4.** Electrical wiring of the robotic arm.

---

## Electronic Architecture

```text
Power Supply
      │
      ▼
 Arduino Uno
      │
      ▼
 Servo Signals
      │
 ┌────┼────┬────┐
 ▼    ▼    ▼    ▼
J1   J2   J3   J4
      │
      ▼
 Mechanical Gripper
```

---

## Design Considerations

The electronics layout was organized to:

- Minimize wiring complexity
- Ensure reliable servo operation
- Simplify troubleshooting
- Support modular assembly
- Allow future hardware expansion

---

# 🧠 Control System

The robotic arm employs an open-loop joint position control strategy using standard hobby servo motors.

Each servo receives a target angle generated by the Arduino microcontroller, allowing coordinated movement of the robotic arm through sequential joint positioning.

---

## Control Workflow

```text
User Command

↓

Arduino Controller

↓

Joint Angle Calculation

↓

Servo Position Commands

↓

Joint Rotation

↓

End Effector Motion
```

---

## Motion Sequence

The embedded software coordinates the motion of all four joints to execute pick-and-place operations.

Typical motion consists of:

1. Move to pickup position.
2. Open gripper.
3. Lower end effector.
4. Close gripper.
5. Lift object.
6. Move to destination.
7. Release object.
8. Return to home position.

---

# 💻 Software Implementation

The control software was developed using the **Arduino IDE** in **C++**.

The firmware is responsible for generating servo control signals and coordinating the movement of each joint.

---

## Software Features

- Servo position control
- Sequential motion execution
- Joint synchronization
- Pick-and-place operation
- Expandable program structure

---

## Software Architecture

```text
Initialize Arduino

↓

Initialize Servos

↓

Receive Motion Command

↓

Calculate Joint Angles

↓

Move Servos

↓

Operate Gripper

↓

Repeat
```

---

The modular software architecture allows additional features such as inverse kinematics, joystick control, or wireless communication to be incorporated with minimal changes to the existing codebase.

---
