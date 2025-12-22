# Zeynel Eren Kınalı

## Robotics & Autonomous Systems Engineer (Student)

Computer Engineering student with a strong focus on **robotics, UAV systems, and autonomous mission design**.  
Experienced in developing **end-to-end autonomous systems**, from simulation and algorithm design to embedded deployment on real robotic platforms. My work primarily targets **search & rescue, navigation, perception, and mission autonomy** for aerial and ground robots.

---

## Technical Focus Areas

- Autonomous UAV systems (fixed-wing & multirotor)
- Robotics simulation and mission testing
- Perception-driven autonomy (vision & sensor fusion)
- Embedded computing for robotics (NVIDIA Jetson, microcontrollers)
- Control systems and navigation algorithms

---

## Core Technical Skills

**Robotics & Autonomy**
- ROS / ROS2 (nodes, navigation stack, move_base)
- Mission-based flight planning (ArduPilot)
- SLAM, waypoint navigation, spiral search algorithms
- Autonomous decision-making pipelines

**Perception & Algorithms**
- Human detection using YOLO + OpenCV
- Sensor fusion (LiDAR, IR distance sensors, encoders)
- Target localization and tracking
- Autonomous search logic for SAR scenarios

**Simulation & Testing**
- Gazebo-based robotic simulation
- ArduPilot SITL
- Scenario-based validation of autonomy logic
- Safe testing of mission behaviors before deployment

**Embedded & Low-Level Systems**
- NVIDIA Jetson (onboard AI inference)
- Arduino-based low-level motor control
- PID control for mobile robots
- LiDAR (YDLiDAR), IR sensors, wheel encoders

**Programming & OS**
- C / C++
- Python
- Linux
- Git

---

## Selected Projects

### Autonomous Search and Rescue (SAR) System
**Fixed-Wing + Multirotor UAV Architecture**

- Designed a two-layer SAR system combining **fixed-wing UAVs for wide-area scanning** and **multirotor UAVs for close-range intervention**.
- Fixed-wing UAV autonomously surveys large areas using mission-based flight planning and endurance-optimized search patterns.
- Upon human detection and operator confirmation, estimated GPS coordinates are transmitted to a multirotor UAV.
- The multirotor UAV autonomously navigates to the target location, executes a **spiral search algorithm**, detects humans using **YOLO-based vision**, deploys emergency payloads (e.g., thermal blanket), lands nearby, and establishes **two-way audio communication**.

---

### Autonomous Mobile Robot – Erasmus+ Internship
**SLAM, Navigation & Low-Level Control**

- Developed an autonomous mobile robot capable of navigating maze-like environments.
- Initial exploration performed using IR distance sensors while simultaneously generating a map via **YDLiDAR-based SLAM**.
- After mapping, autonomous navigation achieved using the **ROS navigation stack** with goal selection through `move_base`.
- Implemented low-level motor control and **PID algorithms** for stable and precise motion.
- Project completed within an international team and achieved **1st place** in the final competition.

---

## Engineering Approach

I approach robotics problems from a **systems perspective**, focusing on:
- Reliability and safety in autonomous behavior
- Clear separation between perception, decision-making, and control layers
- Simulation-first development to reduce real-world risk
- Practical deployment on embedded hardware

---

## Motivation

Motivated to contribute to the development of **reliable, mission-oriented autonomous platforms** for the **Turkish defense and robotics industry**, with a strong interest in UAV autonomy, perception-driven systems, and embedded AI.

---

📍 Türkiye  
📧 Contact: zeynelerenkinali@gmail.com  
🔗 LinkedIn: https://www.linkedin.com/in/zeynelerenk%C4%B1nal%C4%B1/
