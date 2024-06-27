# 2-Axis Robotic Arm

A versatile and efficient 2-axis robotic arm project utilizing three servos, an ESP32 microcontroller, a LiPo battery, and jumper wires.

## Introduction

This project demonstrates the creation of a 2-axis robotic arm controlled by an ESP32 microcontroller. The arm employs three servos to manipulate different axes: one for vertical movement, one for horizontal rotation, and one for an end-effector (such as a gripper). Powered by a LiPo battery, the arm is connected and controlled via jumper wires. This project serves as an excellent introduction to robotics and automation, showcasing how to build and control a robotic arm.

## Hardware Components
- **ESP32**: Microcontroller used to control the servos.
- **Three Servos**:
  - **Base Servo**: Controls the horizontal rotation of the entire arm.
  - **Arm Servo**: Controls the vertical movement of the arm.
  - **Gripper Servo**: Controls the gripper or end-effector of the arm.
- **LiPo Battery**: Provides power to the system.
- **Jumper Wires**: Connect the components.
  
## Usage

1. Power the ESP32 with the LiPo battery.
2. The robotic arm will initialize and be ready for control.
3. Use the Serial Monitor in the Arduino IDE to send commands and control the arm:
    - `'a'` to rotate the base servo left
    - `'d'` to rotate the base servo right
    - `'w'` to move the arm servo up
    - `'s'` to move the arm servo down
    - `'q'` to close the gripper servo
    - `'e'` to open the gripper servo
      
## Contact

Feel free to reach out with any questions or suggestions:

- Email: js7841@srmist.edu.in
