# Lane Follower Robot

## Project Overview
This project involves designing and building a **lane-following robot** that uses sensors to detect and follow a line. The goal is to create a system that accurately follows a path and adjusts its speed and direction based on sensor input.

## Components Used:
1. **Arduino Nano**:  
   The Arduino Nano is the central microcontroller used for controlling the entire robot. It handles sensor data processing, motor control, and makes decisions based on the inputs received from the sensors.

2. **N20 Micrometal Motors (600 RPM)**:  
   Two N20 micrometal motors with a speed of 600 RPM are used to drive the robot. These compact motors provide the required torque and speed for effective movement of the robot on various surfaces.

3. **7-Array Sensor (RoboJunkies)**:  
   A 7-array sensor is used to detect the line. These sensors are arranged to allow the robot to track the path effectively, detecting whether the robot is on track or veering off.

4. **LF2 Carrier Board (RoboJunkies)**:  
   The LF2 carrier board is used to interface with the sensors and motors. It handles motor control and processes sensor data for line-following decisions.

5. **2S Orange 7.4V Battery**:  
   The robot is powered by a 7.4V battery, providing adequate power for the motors and the sensors. This battery is lightweight and suitable for small robots like this lane follower.

6. **Custom-Designed Chassis**:  
   The chassis has been custom-designed to accommodate the motors, sensors, and other components. This design ensures that all parts are securely mounted and balanced, allowing for smooth movement.(Chassis design is attached as a PDF file in this repository).

## Code:
The code for the lane-following robot was fetched from **RoboJunkies** and has been **tuned** as per the size and dimensions of the robot. Modifications were made to ensure that the code works optimally with the specific configuration of our motors, sensors, and chassis used in this project.

## Key Features:
- **Line Detection**: The robot uses IR sensors to detect the line.
- **Speed Control (PID Algorithm)**: The robot uses a **PID (Proportional-Integral-Derivative)** algorithm for precise speed control. This helps in maintaining a steady speed and smoothly adjusting to curves based on sensor feedback.
- **Error Correction**: The robot makes turns and corrects its path based on sensor input.


## Project Objectives:
1. **Basic Line Following**: The robot should follow a simple path.
2. **Speed Adjustments**: Make the robot slow down or turn based on how far off the line it is.
3. **Improved Accuracy**: Implement logic to prevent the robot from overshooting turns or veering off course.

## Repository Contents:
- **Code**: Code for the lane-following algorithm, motor control, and sensor integration.
- **Schematics**: Circuit diagrams and connections.
- **Test Results**: Test data or observations from the robot’s performance.

## How to Run:
1. **Install the required libraries** (list them, e.g., Arduino IDE libraries, sensor libraries, etc.).
2. **Upload the code** to your microcontroller (Arduino Nano).
3. **Set up the hardware**: Connect the motors, sensors, and power supply.
4. **Run the robot** and adjust any necessary parameters for optimal performance.

## Future Enhancements:
- Integrate more sensors for better accuracy.
- Implement a more sophisticated path-following algorithm.

## Lane follower in Action
[Click here to see lane follower in action](https://youtu.be/IQh2VlbWpbw)


## Special Thanks:
A special thanks to **RoboJunkies** for the components,we utilized their **open-source code** as a base for our project, which we modified and tuned according to our robot's size and specifications, which was essential to the successful completion of this project.
