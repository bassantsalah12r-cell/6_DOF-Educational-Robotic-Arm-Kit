<div align="center">

<img src="assets/logo/uni_logo.png" width="130">

# BENHA NATIONAL UNIVERSITY

### Faculty of Engineering

### Mechatronics and Automation Department

<br>

# 🎓 Graduation Project 2026

# 🤖 6_DOF Educational Robotic Arm Kit

### Learn • Visualize • Simulate • Understand Robotics

An interactive educational platform designed to help students understand robotic kinematics through real-time simulation, visualization, and control.

<br>

![Python](https://img.shields.io/badge/Python-3.11-blue)
![PyBullet](https://img.shields.io/badge/PyBullet-Simulation-green)
![Tkinter](https://img.shields.io/badge/Tkinter-GUI-orange)
![ESP32](https://img.shields.io/badge/ESP32-Control-red)

</div>

---

# 📖 Overview

Robotics education often focuses on mathematical equations and theoretical concepts without providing sufficient visualization of robot behavior.

The 6-DOF Educational Robotic Arm Kit was developed to bridge the gap between theoretical robotics concepts and practical implementation.

The platform provides an interactive environment where students can:

✅ Explore Forward Kinematics

✅ Explore Inverse Kinematics

✅ Generate Robot Trajectories

✅ Simulate Robot Motion

✅ Control a Physical Robot Arm

✅ Visualize Mathematical Concepts in Real Time

The system combines software simulation, educational visualization, and hardware integration to create a complete robotics learning experience.

---
## 🖼️ Project Preview

<div align="center">

<img src="assets/screenshots/robotic_arm.png" width="900" alt="6-DOF Educational Robotic Arm">

*Figure 1. Overview of the 6-DOF Educational Robotic Arm Kit.*

</div>

---

# ✨ Key Features

| Feature | Description |
|----------|-------------|
| Forward Kinematics | Calculate end-effector position and orientation |
| Inverse Kinematics | Generate joint angles for a desired pose |
| Path Planning | Generate smooth robot trajectories |
| Robot Simulation | Real-time simulation using PyBullet |
| GUI Interface | User-friendly educational interface |
| Data Visualization | Graphs and performance analysis |
| ESP32 Integration | Physical robot control |
| Educational Content | Learning-focused design |

---

# 🏗️ System Architecture

```text
User
 │
 ▼
GUI Interface (Tkinter)
 │
 ▼
Kinematics Engine
(FK / IK Calculations)
 │
 ▼
Control Module
 │
 ▼
Simulation Engine
(PyBullet)
 │
 ▼
6-DOF Robot Model
```

---

# 🔄 Forward Kinematics Workflow

```text
Start
 │
 ▼
Input Joint Angles
 │
 ▼
Apply DH Parameters
 │
 ▼
Compute Transformation Matrices
 │
 ▼
Calculate End-Effector Pose
 │
 ▼
Visualize Results
 │
 ▼
End
```

---

# 🔄 Inverse Kinematics Workflow

```text
Start
 │
 ▼
Input Desired Pose
 │
 ▼
Inverse Kinematics Solver
 │
 ▼
Generate Joint Angles
 │
 ▼
Validate Solution
 │
 ▼
Visualize Robot Motion
 │
 ▼
End
```

---

# 🔄 Path Planning Workflow

```text
Start
 │
 ▼
Select Start Position
 │
 ▼
Select Goal Position
 │
 ▼
Generate Trajectory
 │
 ▼
Interpolate Waypoints
 │
 ▼
Execute Motion
 │
 ▼
End
```

---

# 📸 Graphical User Interface (GUI)

## 🏠 Home Interface

| Main Window | Student Information |
|:-----------:|:-----------------:|
| <img src="assets/screenshots/home1.png" width="450"> | <img src="assets/screenshots/home2.png" width="450"> |

---

## ⚙️ Forward Kinematics

| Tutorial Videos | Simulation Result |
|:----------------:|:-----------------:|
| <img src="assets/screenshots/fk1.png" width="450"> | <img src="assets/screenshots/fk2.png" width="450"> |

---

## 🎯 Inverse Kinematics

| Tutorial Videos | Calculated Motion |
|:----------:|:-----------------:|
| <img src="assets/screenshots/ik1.png" width="450"> | <img src="assets/screenshots/ik2.png" width="450"> |

---

## 📈 Path Planning

| Tutorial Videos | Robot Movement |
|:---------------------:|:--------------:|
| <img src="assets/screenshots/path1.png" width="450"> | <img src="assets/screenshots/path2.png" width="450"> |

---

## 📈 Torque & Forces

| Tutorial Videos | Robot Movement |
|:---------------------:|:--------------:|
| <img src="assets/screenshots/torque1.png" width="450"> | <img src="assets/screenshots/torque2.png" width="450"> |

---

## 🤖 Robot Simulation

| Simulation View | End-Effector Motion |
|:---------------:|:-------------------:|
| <img src="assets/screenshots/sim1.png" width="450"> | <img src="assets/screenshots/sim2.png" width="450"> |

---

## 🔧 Robot Control

| Control Panel | Real-Time Operation |
|:-------------:|:-------------------:|
| <img src="assets/screenshots/control1.png" width="450"> | <img src="assets/screenshots/control2.png" width="450"> |


# 🛠️ Technologies Used

- Python 3.11
- Tkinter GUI
- PyBullet Simulation
- NumPy
- Matplotlib
- C++
- ESP32
- Robotics Algorithms
- URDF Robot Modeling

---

# 👨‍🏫 Supervisor

<div align="center">

<img src="assets/team/amro_shafik.jpg" width="180">

## Dr. Amro Shafik

Project Supervisor

</div>

---

# 👥 Development Team

<div align="center">

| | | | |
|:-:|:-:|:-:|:-:|
| <img src="assets/team/bassant.jpg" width="140"><br><b>Bassant Salah Rashad</b><br>Software Team | <img src="assets/team/shahd.jpg" width="140"><br><b>Shahd Ahmed Mahboub</b><br>Mechanical & Software Team | <img src="assets/team/haneen.jpg" width="140"><br><b>Haneen Ahmed Hamed</b><br>Software Team | <img src="assets/team/fatema.jpg" width="140"><br><b>Fatema Ahmed Saad</b><br>Mechanical Team |
| <img src="assets/team/seif.jpg" width="140"><br><b>Seif Allah Wael Hassan</b><br>Software & Hardware Team | <img src="assets/team/giovanni.jpg" width="140"><br><b>Giovanni El-Amir Gaber</b><br>Hardware Team | <img src="assets/team/mina.jpg" width="140"><br><b>Mina Bahgat Bolus</b><br>Mechanical Team | <img src="assets/team/mohamed.jpg" width="140"><br><b>Mohamed Ahmed Ahmed</b><br>Mechanical Team |

</div>

---

# 🚀 Future Work

- ROS2 Integration
- AI-Based Motion Planning
- Computer Vision Integration
- Real Robot Deployment
- Web-Based Learning Platform
- Multi-Robot Simulation

---

# 📜 License

This project was developed as a Graduation Project at Benha National University for educational and research purposes.

---

<div align="center">

### ⭐ Thank you for visiting our project

Made with ❤️ by the Mechatronics and Automation Engineering Team

</div>

<div align="center">

⭐ If you like this project, don't forget to star the repository.

</div>
