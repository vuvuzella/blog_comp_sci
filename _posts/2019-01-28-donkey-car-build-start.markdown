---
layout: post
title:  "Donkey Car Build Start"
date:   2019-01-28 01:20:00 UTC+1000
image:  donkey-start.jpg
category: Projects
tags:   [Donkey Car, Autonomous, Self Driving Car, Computer Vision]
---

# Donkey Car Part 1

## My First Weekend Project!

My first of the many weekend projects I plan to have. This is the Donkey car, an open source mobile robotics platform that was used in numerous self-driving and autonomous races in the United States.

The hardware and software are all open source. Documentation of how to build the car from the ground up is in the [Donkey car](http://docs.donkeycar.com/) website. Github for the software is located [here](https://github.com/autorope/donkeycar/)

There is also a youtube video (quite long!) that steps you through the build. [Watch it here](https://www.youtube.com/watch?v=byRLYkZkJZE)

## Impression on the Documentations

The docs for the hardware and software are sufficient to get you started, howver, some small information are not stipulated. One such example is when to connect the servo and DC motors to the PWM controller. I had to watch the hour long video just to be sure of what I was doing

## New things learned

1. Fusion 360
    - I started dabbling with Fusion 360. I needed to splice up the roll cage so that it would be much cheaper to print
    - 
2. Adafruit PCA9685 PWM library and ServoKit Library
    - Working out to use this library to test the hardware before moving on to the Donkey Car container
3. Mechanical Stuff

[3D Printing at Uni]()

![Donkey Car](/img/donkey-start.jpg)

![Donkey Car](/img/donkey-start-2.jpg)

## Milestones achieved

1. Hardware Build
    - Acquired the parts, except for the roll cage. For now I made a makeshift mount for the camera
2. Power up Raspberry Pi
    - Raspberry pi is currently powered by 1 5V power bank.
3. Test The camera
    - Made a python test app to take pictures
    - Made a pygame app to see the preview of the camera

## Upcoming Tasks

1. Test the PCA9685 and run the servo and DC motor using python
2. Install the Donkey Car Software
3. Trial run
4. Acquire a wireless donggle
5. 3D print the roll cage