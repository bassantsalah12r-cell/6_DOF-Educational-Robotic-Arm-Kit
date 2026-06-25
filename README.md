# 6_DOF-Educational-Robotic-Arm-Kit
<div align="center">

### Learn • Visualize • Simulate • Understand Robotics

An interactive educational platform designed to help students understand robotic kinematics through real-time simulation, visualization, and control.

![Python](https://img.shields.io/badge/Python-3.11-blue)
![PyBullet](https://img.shields.io/badge/PyBullet-Simulation-green)
![Tkinter](https://img.shields.io/badge/Tkinter-GUI-orange)
![ESP32](https://img.shields.io/badge/ESP32-Control-red)

</div>

---

## 📖 Overview

Robotics education often focuses on mathematical equations and theoretical concepts without providing sufficient visualization of how robot motion is generated.

This platform bridges the gap between theory and practice by allowing students to interactively explore:

- Forward Kinematics (FK)
- Inverse Kinematics (IK)
- Path Planning
- Robot Simulation
- Joint Control
- Real-Time Visualization

The system combines educational content with interactive simulation to create a powerful learning environment for robotics students.

---

## 🖼️ Main Interface

<p align="center">
<img src="assets/screenshots/main_gui.png" width="900">
</p>

---

## ✨ Features

### 🔹 Forward Kinematics
- Calculate end-effector position
- Visualize robot movement
- Display transformation results

### 🔹 Inverse Kinematics
- Solve desired robot pose
- Generate joint angles automatically
- Verify solutions through simulation

### 🔹 Path Planning
- Generate trajectories
- Interpolate waypoints
- Execute smooth robot motion

### 🔹 Simulation
- Real-time robot visualization
- Physics-based environment using PyBullet
- Interactive robot control

### 🔹 GUI
- User-friendly interface
- Educational visualization
- Easy navigation between modules

### 🔹 Data Visualization
- Joint angle monitoring
- Position tracking
- Performance graphs

---

# 🏗️ System Architecture

<p align="center">
<img src="assets/architecture.png" width="1000">
</p>

### Workflow

```text
User
  ↓
GUI Interface
  ↓
Kinematics Engine
  ↓
Control Module
  ↓
Simulation Engine
  ↓
Robot Model
```

---

# 🔄 Forward Kinematics Flow

<p align="center">
<img src="assets/fk_flowchart.png" width="700">
</p>

```text
Start
 ↓
Input Joint Angles
 ↓
Apply DH Parameters
 ↓
Compute Transformation Matrices
 ↓
Calculate End-Effector Position
 ↓
Visualize Results
 ↓
End
```

---

# 🔄 Inverse Kinematics Flow

<p align="center">
<img src="assets/ik_flowchart.png" width="700">
</p>

```text
Start
 ↓
Input Desired Pose
 ↓
IK Solver
 ↓
Generate Joint Angles
 ↓
Validate Solution
 ↓
Visualize Robot Motion
 ↓
End
```

---

# 🔄 Path Planning Flow

<p align="center">
<img src="assets/path_planning_flowchart.png" width="700">
</p>

```text
Start
 ↓
Select Start Position
 ↓
Select Goal Position
 ↓
Generate Trajectory
 ↓
Interpolate Waypoints
 ↓
Execute Motion
 ↓
End
```

---

# 📸 Screenshots

## Home Screen

<img src="assets/screenshots/home.png">

## Forward Kinematics

<img src="assets/screenshots/fk.png">

## Inverse Kinematics

<img src="assets/screenshots/ik.png">

## Simulation

<img src="assets/screenshots/simulation.png">

---

# 🎥 Demonstration

<p align="center">
<img src="assets/demo.gif">
</p>

---

# 🛠️ Technologies Used

- Python
- Tkinter
- PyBullet
- NumPy
- Matplotlib
- C++
- ESP32
- Robotics Algorithms
- DH Parameters

---

# 📂 Project Structure

```text
Robotic-Education-Platform/
│
├── GUI/
├── Kinematics/
├── Simulation/
├── Control/
├── ESP32/
├── Documentation/
├── assets/
│   ├── screenshots/
│   ├── architecture.png
│   ├── fk_flowchart.png
│   ├── ik_flowchart.png
│   └── demo.gif
│
├── requirements.txt
├── README.md
└── main.py
```

---

## 👨‍🏫 Supervisor

<div align="center">

<img src="assets/team/amro_shafik.jpg" width="150" style="border-radius:50%;">

### Dr. Amro Shafik

Project Supervisor

</div>

---

# 👥 Development Team

<table align="center">
<tr>

<td align="center">
<img src="assets/team/bassant.jpg" width="120"><br>
<b>Bassant Salah Rashad</b><br>
Robotics & Software Developer
</td>

<td align="center">
<img src="assets/team/shahd.jpg" width="120"><br>
<b>Shahd Ahmed Mahboub</b><br>
Software Developer
</td>

<td align="center">
<img src="assets/team/haneen.jpg" width="120"><br>
<b>Haneen Ahmed Hamed</b><br>
Software Developer
</td>

</tr>

<tr>

<td align="center">
<img src="assets/team/fatema.jpg" width="120"><br>
<b>Fatema Ahmed Saad</b><br>
Software Developer
</td>

<td align="center">
<img src="assets/team/seif.jpg" width="120"><br>
<b>Seif Allah Wael Hassan</b><br>
Embedded Systems Developer
</td>

<td align="center">
<img src="assets/logo.png" width="120"><br>
<b>Benha National University</b><br>
Mechatronics Engineering
</td>

</tr>
</table>


---

# 🎓 Supervisor

Dr. ______________________

---

# 🚀 Future Work

- ROS2 Integration
- AI-Based Motion Planning
- Computer Vision Integration
- Real Robot Deployment
- Web-Based Platform

---

# 📜 License

This project is developed for educational and research purposes.

---

<div align="center">

⭐ If you like this project, don't forget to star the repository.

</div>
