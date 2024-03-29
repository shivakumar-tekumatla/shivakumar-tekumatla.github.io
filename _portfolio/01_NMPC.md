---
title: "Nonlinear Model Predictive Control for Mobile Robots"
excerpt: "NMPC  algorithm for collision-free navigation of a mobile robot in unknown and dynamic environments

<img src='https://github.com/shivakumar-tekumatla/shivakumar-tekumatla.github.io/blob/master/files/GIFs/NMPC3.gif?raw=true' width =400  />"
collection: portfolio
---

In this project, we present different methods that are used for navigation of a mobile robot in unknown and
dynamic environments. We compare various methods for realtime navigation of a mobile robot , and present collision free control using generalized velocity obstacles(VO) and non-linear model predictive control(NMPC). In this work, we also discuss about the usage of various physical constraints of a general
mobile-robot. The disadvantages of a physical constrains for motion planning are tackled using these methods. Generalised Velocity-Obstacle provides a combined solution for both holonomic
and non-holonomic robots. NMPC , a variation of MPC, that is used here , does not require any reference trajectory , thus performing computationally well. We compared these two methods for navigation in dynamic environments. We use the performance of these algorithms in complete static or a few dynamic obstacle environment as baseline for testing other cases. We tested the performance of these algorithms using different evaluation parameters. We also presented a clear understanding of usage of various types of adhoc parameters for each of these algorithms. Finally, we simulate our results in RVIZ simulation platform using ROS framework. We see the application of our methods where robot needs to navigate environments such a hospital corridor with humans other robots , social robots such as in airports etc.

# Results 
<!-- <img src="https://github.com/shivakumar-tekumatla/shivakumar-tekumatla.github.io/blob/master/files/GIFs/NMPC1.gif" alt="gif" >  -->
Without Boundary:

<img src='https://github.com/shivakumar-tekumatla/shivakumar-tekumatla.github.io/blob/master/files/GIFs/NMPC1.gif?raw=true' />

With Boundary:
<img src='https://github.com/shivakumar-tekumatla/shivakumar-tekumatla.github.io/blob/master/files/GIFs/NMPC2.gif?raw=true' />

[Git Hub](https://github.com/shivakumar-tekumatla/NMPC-and-VO-for-Mobile-Robot) 

Report for this project can be [downloaded from here](https://github.com/shivakumar-tekumatla/shivakumar-tekumatla.github.io/blob/master/files/NMPC.pdf). 

Instructor: [Jane Li](http://labs.wpi.edu/hiro/zhi-jane-li/)