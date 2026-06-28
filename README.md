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
