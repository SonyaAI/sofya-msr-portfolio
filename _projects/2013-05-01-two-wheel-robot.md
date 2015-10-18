---
layout: project
title: Two-Wheel Balancing Robot
date: May, 2013
image: https://raw.githubusercontent.com/SonyaAI/sofya-msr-portfolio/gh-pages/public/images/two-wheel-robot.jpg
---

## Overview
The main goal of this project was construction of a small (~1 foot tall), two-wheeled, self-balancing robot similar to a Segway.  Such a device is a type of inverted pendulum.  The project was deemed appropriate because completion would require use of skills from multiple disciplines of engineering and physics.  Some of the major tasks required were mathematically modeling the device from equations of motion in Matlab/Simulink, drawing CAD schematics of the physical apparatus, programming a microcontroller, and physically wiring all required electronic hardware together.  In addition to the primary goal of a self-balancing prototype, one “stretch” goal conceived to be attempted after the primary goal was achieved was position control.  This was never attempted but remains possible if this project is to be continued.

* Youtube video: https://www.youtube.com/watch?v=nkP_GO6Jyz8
* Project website: https://sites.google.com/site/selfbalancingrobot2013/home 

### Main Components
* Main Components: Orangutan SCP-1284p Microcontroller, Inertial Measurement Unit (IMU), Bluetooth Module
* The IMU contains sensors that were used to measure the tilt angle.  This information was sent to the microcontroller
* The microcontroller then uses a PID Controller algorithm to analyze the data and set the motor speeds accordingly
* Bluetooth communication was used to send commands to the robot (reset, power down, set PID values)

