# Robot Manipulator - Pick and Place

## Project Overview
This project involves programming a robotic manipulator using MATLAB and LEGO Mindstorms EV3 to perform pick-and-place operations. The robot is equipped with three motors and multiple sensors for controlled movements and precise task execution. Key features include homing, picking, placing, and height measurement operations implemented through inverse kinematics and PI control.

---

## Key Features
- **Pick-and-Place Operations:** Robot arm moves objects between predefined stations (A, B, and C).
- **Inverse Kinematics:** Calculated joint angles for accurate positioning of the robotic arm.
- **PI Controller:** Ensures smooth movements with precise control over arm and base rotations.
- **Sensor Integration:** Utilized touch sensors and encoders for collision avoidance and accurate positioning.

---

## Objectives
- Develop a MATLAB program to control a robotic manipulator for pick-and-place tasks.
- Implement inverse kinematics to calculate joint angles.
- Design a PI controller for base and arm rotation.
- Enable real-time sensor feedback for safe and efficient operations.

---

## Skills Demonstrated
- **Robotics Programming:** MATLAB coding for robot control and kinematic calculations.
- **Control Systems:** Designed and tuned a PI controller for smooth robotic movements.
- **Inverse Kinematics:** Computed angles for precise positioning of the robotic arm.
- **Sensor Integration:** Interfaced touch sensors and encoders with the LEGO Mindstorms EV3 system.

---

## Components and Specifications
### Hardware:
- **Robot Base:** LEGO Mindstorms EV3
- **Motors:** 
  - Motor A: Gripper control
  - Motor B: Arm rotation
  - Motor C: Base rotation
- **Sensors:**
  - Touch Sensors (2 units)
  - Encoders (3 units, integrated with motors)
- **Links Dimensions:**
  - Link 1: 50 mm
  - Link 2: 98 mm
  - Link 3: 185 mm
  - Link 4: 110 mm

### Software:
- MATLAB for programming and simulation
- USB connection for robot control and data communication

---

## System Architecture
### Functional Highlights:
1. **Homing Function:** Initializes the robot's position to station A.
2. **Height Measurement:** Uses ultrasonic readings to ensure precise positioning.
3. **Task Execution:**
   - Moves objects between stations A, B, and C based on task requirements.
   - Computes kinematics to determine coordinates for picking and placing.

---

## Installation and Usage
### Requirements:
- LEGO Mindstorms EV3 kit
- MATLAB with LEGO Mindstorms support
- USB cable for robot communication

### Steps:
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/robot-manipulator-pick-place.git
