---
layout: single
title: "Projects"
permalink: /projects/
author_profile: true
toc: true
---

### [Ball-following Robot](https://github.com/zainasir/BallFollower)
ROS project where a TurtleBot follows a red ball while maintaining a distance of 1 meter. I used OpenCV to detect a sphere and the most red pixel in the camera's viewport to pinpoint the ball's exact location. After finding the distance of the ball using the depth camera, linear and angular velocity commands were sent to the TurtleBot, allowing it to follow the red ball while maintaining the distance.

![Gif showing a demo of this project](/images/ball-follower-robot-demo.gif)

### [Spotted Lantern Fly Detection through Drones](https://github.com/boubinjg/SpottedLanternFly)
The aim of this project was to enable drones to be able to detect Spotted Lantern Flys through object detection. This project was completed as part of the Digital Ag Hackathon at the Cornell Institute for Digital Agriculture. We collected a custom dataset, retrained YOLOv8, and integrated trained model in a drone for aerial surveillance.

![Gif showing a demo of this project](/images/slf-demo.gif)

