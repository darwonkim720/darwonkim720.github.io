--- 
title: "4DOF Manipulator [Current]"
excerpt: "4DOF manipulator using servos, Arduino, and ROS"
collection: portfolio
---

This is another ongoing project I have recently started working on. My endgoal is to control the manipulator using an IMU sensor and communicate through ROS. 

Currently, I have a simple manipulator built using breadboards, an Arduino UNO R4 Minima, and four 9g micro servos. 
This can be controlled in two different ways. Through the potentiometers on the breadboard, or through the rosserial terminal. 
Some problems I have encountered so far are: 
- The 9g micro servos I am using have a resolution of 5 degrees, which causes jittery, abrupt movement. 
- I can only publish specific values for each servo motor through rosserial.
- I need better materials to build the manipulator.

Possible solutions are: 
- Replace the motors with stepper motors.
- Publsih Twist messages through keyboard teleop using ROS.

<br>
<br>

![manipulator_1](https://github.com/darwonkim720/darwonkim720.github.io/assets/150773404/4432f7e9-a0b8-4ddc-a650-f42ba2f5cdab)


![manipulator_2](https://github.com/darwonkim720/darwonkim720.github.io/assets/150773404/c33f9398-3839-48d8-a5d6-28db8fd33b86)
