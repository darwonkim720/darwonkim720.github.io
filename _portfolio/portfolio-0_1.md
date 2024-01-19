---
title: "4DOF Manipulator" [Current]"
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
