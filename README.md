Engineering materials
====

This repository contains engineering materials of a self-driven vehicle's model participating in the WRO Future Engineers competition in the season 2022.

## Content

* `t-photos` contains 2 photos of the team (an official one and one funny photo with all team members)
* `v-photos` contains 6 photos of the vehicle (from every side, from top and bottom)
* `video` contains the video.md file with the link to a video where driving demonstration exists
* `schemes` contains one or several schematic diagrams in form of JPEG, PNG or PDF of the electromechanical components illustrating all the elements (electronic components and motors) used in the vehicle and how they connect to each other.
* `src` contains code of control software for all components which were programmed to participate in the competition

## Introduction

Our project for this year is a robotic vehicle needs to drive autonomously 
on a parkours that randomly changes each round. 
We used the Lego MINDSTORMS EV3 robotics kit to build our vehicle.
Our main brick, i.e., control center and power station for our 
robot is connected to two color sensors, one ultrasonic sensor
one gyro sensor. 
We have a steering actuator powered by a medium motor
and a rear-wheeled drive powered by a large motor.

We programmed the robot to estimate the state of the parkours and the 
vehicle itself through the different sensors attached to it.
