# Micro Mouse Project
# Overview
Welcome to the Micro Mouse Project! This project aims to develop the power supply and sensor submodules for an autonomous robot (Micro Mouse) capable of navigating through a maze. The robot utilizes sensors, motors, and a microcontroller to detect walls, make decisions, and move through the maze.

# Features
Obstacle Detection:
The sensor circuit can transfer information about the presence of obstacles in the path of the micro mouse robot (the presence of maze walls in front, and on the sidesm of the robot)

# Components
Microcontroller: The STM32L476 microcontroller to process sensor data and control movements.
Sensors: Infrared or ultrasonic sensors for wall detection.
Motors: To control movement.
Power Supply: 1S1P 18650 LiPo battery suitable for the mouse's power requirements.
Frame: Pre built frame that will house all the components of the mouse.

# Getting Started
# Prerequisites
Theory: Basic understanding of electronics.
Software: Preferrably VS Code or any suitable microcontroller programming environment (STM32CubeIDE works great as well).

# Implementation/Testing
Assemble the Hardware:
Put the Power and Sensor boards together.
Connect all components to the microcontroller as per the wiring diagram provided in the documentation.
Upload the Code:
Open the provided source code in your programming environment.
Upload the code to the microcontroller.
Power Up:
Insert the batteries and power up the Micro Mouse.
Observe that all the required components power up and behave as expected
Troubleshooting
No Movement: Check motor connections and power supply circuit.
Inaccurate Obstacle Detection: Ensure sensors are properly aligned and calibrated, inspect software for any errors.
Code Errors: Verify the code is correctly uploaded and there are no syntax errors.

# Contributing
We currently do not welcome contributions to improve the Micro Mouse Project!.

# License
This project is licensed under the GNU GENERAL PUBLIC LICENSE. See the LICENSE file for more details.

# Contact
For any questions or feedback, please contact us atMSNKAT010@myuct.ac.za or SMLPRA001@myuct.ac.za

Thank you for exploring the Micro Mouse Project! Enjoy building and programming your micro mouse
