# robot localization
Brooke Moss and Isha Goyal
October 13, 2023

Questions to answer:
1. What was the goal of your project?
2. How did you solve the problem? (Note: this doesn’t have to be super-detailed, you should try to explain what you did at a high-level so that others in the class could reasonably understand what you did).
3. Describe a design decision you had to make when working on your project and what you ultimately did (and why)? These design decisions could be particular choices for how you implemented some part of an algorithm or perhaps a decision regarding which of two external packages to use in your project.
4. What if any challenges did you face along the way?
5. What would you do to improve your project if you had more time?
6. Did you learn any interesting lessons for future robotic programming projects? These could relate to working on robotics projects in teams, working on more open-ended (and longer term) problems, or any other relevant topic.


## Introduction
A challenge with tracking a robot’s position is the unreliability of odometry data. Thus, our challenge was to use data from the robot’s laser scanner in conjunction with its odometry data to determine where it was in a known map. Our approach was based on an algorithm called a particle filter, which probabilistically narrows down the robot’s position.

## Approach
High level, then implementation?

## Process
Design decisions (resampling + adding noise? choosing the heaviest particle, not the avg?); Challenges

## Looking Forward
Faster (used lots of loops); Robot kidnapping?
