## Thesis Chapters outline

1. Introduction
    - Background
    - Challenges and Research
    - Objectives of the Project
    - Limitations of the Study
    - Structure of the Thesis

2. State of the Art Review
    2.1 Robotic Manipulator Control Approaches
        2.1.1 Mobile Manipulation Tasks
    2.2 Traditional Control Approaches
    2.3 Deep Reinforcement Learning: a Data-Driven Approach
        2.3.1 Challenges in Data-Driven Approaches
    2.4 Whole-body mobile manipulator control
        2.4.1 MPC+IK for articulated object manipulation
        2.4.2 Deep Reinforcement Learning for high DoF control
        2.4.3 Mobile Manipulation with Imitation Learning
        2.4.4 Comparison of Model-Based and Data-Driven approaches
    2.5 Addressing the Simulation-to-Reality Gap
    2.6 Object Detection and Grasping
        2.6.1 Grasping Soft Objects

3. Robotic Platform for Mobile Manipulation
    3.1 Mobile Robot Platform
    3.2 Robotic Arm Manipulator
       * Issues with Igus Rebel motors' encoders and calibration
    3.3 Sensors and Perception
       * Issues with Intel Realsense calibration
    3.4 Soft Gripper Actuator
    3.5 3D Printed Mounts Design
       * Issues with the laboratory's 3D printer
    3.6 Batteries and Power Management

4. Software Architecture and Simulation Environments
    4.1 ROS2 Control Interface for Igus Rebel Arm
    4.2 Joint Trajectory Controller for Igus Rebel Arm
    4.3 MoveIt2 Simulation Environment
    4.4 Robotic Arm Visual Servoing
    4.5 Soft Gripper Pneumatic Pump Actuation
    4.6 Autonomous Navigation with NAV2
       * Issues with 3D LIDAR in navigation
       * Dynamic Obstacle Avoidance with NAV2
    4.7 Ignition Gazebo Simulation Environment
    4.8 Parking Algorithm for Mobile Robot
    4.9 Aruco Marker Detection and Pose Estimation
        Multi Aruco Setup for Plane Estimation
    4.10 Object Detection with YOLOv8
    4.11 Collision Avoidance with Octomap 
    4.12 ROS2 Actions Client-Server Architecture for High-Level Tasks

5. Experimental Setup and Demonstrations
    5.1 Description of the Demonstrations and Objectives
    5.2 Aruco Follower Demo
        5.2.1 End Effector Positioning
    5.3 Button Presser Demo
        5.3.1 Objective and Description of the Demo
        5.3.2 Buttons Setup Box and End Effector Setups
        5.3.3 
        5.3.4 End Effector Positioning and Arm Trajectories
        5.3.5 Mobile Button Presser Demo
        5.3.6 Experimental Challenges
    5.4 Object Picking Demo
        5.4.1 Objective and Description of the Demo
        5.4.2 Plants, Colored Balls and Fruits Setup
        5.4.3 Algorithm for Object Position Estimation
        5.4.5 Demo with Manual User Input
        5.4.6 Demo with Object Detection Neural Network
        5.4.7 Mobile Fruit Picking Demo
        5.4.8 Experimental Challenges

6. Results and Future Work
   - Potential of Mobile Manipulation
   - Applications and Successes
   - Limitations and Shortcomings
   - Project and Code Legacies
   - Future Work
       * Higher-Level Tasks Composition with Behavior Trees
       * Large Language Models for Text-to-Actions Command