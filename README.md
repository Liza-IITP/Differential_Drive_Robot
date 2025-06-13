# Differential_Drive_Robot

This mini project simulates a **2-wheel differential drive robot** using **ROS 2 (Humble)** and **Gazebo**. It includes:
- URDF/Xacro robot model
- Launch files for Gazebo simulation
- ROS 2 nodes for controlling robot movement

## 📁 Folder Structure
ws_ddmobile/
├── src/
│   └── mobile_dd_robot/
│       ├── include/
│       ├── launch/
│       │   └── gazebo_model.launch.py
│       ├── model/
│       │   ├── robot.xacro
│       │   └── robot.gazebo
│       ├── src/
│       ├── CMakeLists.txt
│       └── package.xml
