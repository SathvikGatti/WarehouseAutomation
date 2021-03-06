# Warehouse Automation Using ROS and UR5 robotic arms.
This is a simulation based warehouse automation project that is built with Robotic Operating System(ROS) and simulated in the Gazebo simulator.
It involves two UR5 robotic arms working in a warehouse scene that automate the process of sortation in a warehouse. They work in sync to pick and sort packages
based on priority. 
The first arm picks and places the packages on to the conveyor belt based on priority, this conveyor belt then carries the package to the second ur5 arm which then picks and segregates the packages in to sepatrate boxes or conveyors for shipping based on priority.
The priority of the packages are depicted by the colour of the package.
The priority structure:
* Red - High
* yellow - Medium
* Green - Low


## Tech stack
* ROS  melodic.
* rospy
* cmake
* Gazebo for simulation.
* Ubuntu 18.04 LTS bionic beaver OS.
* OpenCV (computer vision in order to capture the packages on the shelf. )
* Pyzbar library(for decoding the QR codes which contains the package specific information that is required to sort pick packages based on priority.)
* RViz (for motion planning.)

The simulation run of the project can be viewed here: https://drive.google.com/drive/folders/1EmKTsNSPSyt66-qqJYsOdgeVhdPKZmTD
