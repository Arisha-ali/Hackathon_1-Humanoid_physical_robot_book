# Module 1 Research: Foundational Topics

This document contains the initial research findings for Module 1, covering ROS 2, Python agents for robotics, and URDF.

## 1. ROS 2 (Robot Operating System 2)

ROS 2 is a set of software libraries and tools that help you build robot applications. It is a major redesign of ROS 1 that adds support for real-time applications, smaller embedded systems, and more.

### Further Research Questions

To proceed with this topic, we should explore the following:

*   What are the core concepts of ROS 2? (e.g., nodes, topics, services, actions)
*   How do you install it on different operating systems (Linux, Windows, macOS)?
*   How do you start a new project or create a package in ROS 2?
*   What are the essential tools and commands (e.g., `colcon`, `ros2 topic`, `ros2 launch`)?
*   How can we troubleshoot common issues in a ROS 2 setup?

## 2. Python Agents for Robotics

Python agents in robotics are autonomous software programs that can perceive their environment, make decisions, and actuate a robot. Python is a popular choice due to its extensive libraries for AI and robotics.

### Key Concepts

*   **Perception**: Gathering data from sensors (cameras, LiDAR, etc.) using libraries like OpenCV.
*   **Reasoning**: Processing information and making decisions using AI algorithms.
*   **Learning**: Improving performance over time using machine learning libraries like TensorFlow or PyTorch.
*   **Action**: Executing decisions by controlling motors and other actuators.

### Relevant Frameworks and Libraries

*   **ROS 2**: Provides a robust framework for communication between different parts of a robotic system.
*   **LangChain, Microsoft AutoGen, CrewAI**: Frameworks for building autonomous AI agents.
*   **PyBullet**: A physics simulator for testing and developing robotics algorithms.
*   **OpenCV**: A library for computer vision.
*   **NumPy, SciPy**: For numerical and scientific computing.

## 3. URDF (Unified Robot Description Format)

URDF is an XML file format used in ROS to describe all aspects of a robot model. This includes:

*   **Links**: The rigid parts of the robot.
*   **Joints**: The connections between links, defining how they move relative to each other.
*   **Visuals**: The 3D models used to represent the robot in simulations and visualizations.
*   **Collisions**: The geometry used for collision detection.
*   **Inertia**: The mass and rotational inertia of each link.

### Further Research Questions

To effectively use URDF, we need to understand:

*   What is the detailed syntax of the URDF format?
*   How do you create a URDF file from scratch for a custom robot?
*   How can you modify an existing URDF file?
*   What are the best practices for creating clean and efficient URDF files?
*   How can URDF be converted to other formats (e.g., SDF for Gazebo)?
*   How do you integrate URDF with simulation tools like Gazebo and Unity?
