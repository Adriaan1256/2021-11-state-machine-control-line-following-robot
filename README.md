# State Machine Control for a Line-Following Robot

Control Systems – Practical Assignment  
University of Pretoria  
Completed: November 2021

---

## Project Overview

This project focuses on the implementation and analysis of a **state-based control system for a line-following robot**.

The control logic governs how the robot reacts to sensor inputs and transitions between different behavioural states to maintain alignment with a track.

The system integrates sensor feedback, motor control, and decision logic to ensure stable navigation.

👉 **[View Full Project Report (PDF)](docs/EBB320_Practical_Assignment_3.pdf)**

---

## Objectives

- Design a **state-based control system** for a line-following robot
- Implement behaviour logic using a **finite state machine**
- Integrate sensor feedback into control decisions
- Control robot motion through motor commands
- Analyse system behaviour during different navigation scenarios
- Evaluate how control logic influences robot stability and performance

---

## Methodology

The system was implemented using a **finite state machine architecture** where each state represents a specific behavioural mode of the robot.

Sensor readings determine transitions between states, allowing the robot to react dynamically to its position relative to the line.

Motor commands are generated based on the current state to adjust the robot's movement and maintain alignment with the track.

The system design includes:

- sensor input processing
- decision logic using state transitions
- motor control output generation
- behavioural analysis through experimentation

---

## Tools & Technologies

- Embedded control systems
- Finite State Machines (FSM)
- Arduino-based robot platform
- Optical line sensors
- DC motor control
- Embedded C programming

---

## Notes

This repository contains the original academic report submitted for the course.

👉 The **implementation code is included in the appendix section of the report**.
