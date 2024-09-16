---
marp: true
title: Robotic Workcell for Automated Bending Process
paginate: true
theme: beam
size: 4:3
header: "Robotic Workcell for Automated Bending Process"
footer: "Shivam Shivam"
---

## Robotic Workcell for Automated Bending Process  
**Automating Metal Sheet Bending with Precision**

- Presenter: Shivam Shivam  
- Date: 16 September 2024

---

# Introduction

**Overview:**

- Industry 4.0's impact on manufacturing
- Automation of manual labor in bending processes
- Collaborative robotic systems for bending

---

# Problem Statement & Objectives

**Problem Statement:**

- Manual bending is labor-intensive and prone to human error.
- Automation requires precision in detecting, bending, and handling.

**Objectives:**

1. Develop a robotic workcell for automated bending.
2. Integrate vision sensors for sheet detection and angle measurement.
3. Build a web-based UI for real-time monitoring.

---

# Literature Review

**Key Technologies:**

- Robotic automation in manufacturing
- Evolution of automated bending processes
- Industry 4.0: Cyber-Physical Systems (CPS) and Digital Twins

*Transition:* Focus shifts to system design and hardware.

---

# System Design Overview

- Key components: Bending machine, handling robot, storage station, vision sensors
- Simulation with ROS (Robot Operating System) and Gazebo software
- System layout and flow of materials and data

---

# Robotic Workcell Components

**Bending Machine:**

- AMADA HFP80-25 NT for automated bending

**Handling Robot:**

- 7-axis KR1410 for metal sheet handling

**Vision Sensors:**

- Two VISOR® cameras for detection and quality control

---

# Hardware Integration

- **Robot and Camera Setup:** Placement of cameras for feature detection
- **Storage Station & Unloading Station:** Coordination between robot and subsystems

---

# Software Development & UI

- Control software for robotic system
- Integration of ROS with a web-based interface
- **Web UI features:** Real-time monitoring, robot control, and 3D visualization

---

# System Networking & Communication

- **PLC Integration:** Controls for bending machine and communication between the KR robot and cameras
- **Profinet Setup:** Data transfer and synchronization between devices

*Transition:* Moving to system testing and evaluation.

---

# Calibration and Testing

- Kinematic and hand-eye calibration for robot and cameras
- Testing procedures for sheet pickup, bending, and inspection

---

# Experimental Results

**Key Metrics:**

- Performance evaluation through tests
- Angle measurement accuracy and calibration results
- Bending operation analysis

---

# Discussion & Future Work

- **Strengths:** High precision, reduced manual labor, flexible configuration
- **Limitations:** Calibration and motion planning challenges
- **Future Research:** Software updates for improved handling and real-time feedback

---

# Conclusion

- **Summary:** Automated bending increases throughput, precision, and safety
- **Impact:** Significant improvements in industrial automation

