# ROS Projects

A curated collection of projects built around the **Robot Operating System (ROS)**. This repository serves as a resource hub for robotics enthusiasts exploring ROS and ROS2 technologies.

---

## Installation Requirements

- [Robot Operating System (ROS)](http://wiki.ros.org/ROS/Installation)
- [Robot Operating System 2 (ROS2)](https://docs.ros.org/en/humble/Installation.html)

---

## Projects

### 1. MazeBot

MazeBot is an innovative project implemented in **ROS2**, showcasing a robot's ability to navigate and solve mazes using computer vision. It highlights the fusion of ROS2 capabilities with advanced vision techniques, enabling the robot to autonomously navigate through maze environments.

**Installation & Usage**

1. Copy the `mazebot` directory into your ROS2 workspace and run:
   ```bash
   colcon build
   ```
2. Launch the project:
   ```bash
   ros2 launch mazebot mazebot_camera_maze.launch.py
   ```

---

### 2. ROS Navigation Stack

A foundational **ROS** implementation exploring core navigation concepts such as **gmapping** and **SLAM**. Designed as a starting point for those new to ROS navigation, this project provides essential insights into the ROS navigation stack.

**Installation & Usage**

1. Copy the `ros navigation stack` directory into your ROS workspace and run:
   ```bash
   catkin_make
   ```
2. Launch the navigation:
   ```bash
   roslaunch navigation navigation.launch
   ```

---

## License


This repository is for educational and learning purposes.

