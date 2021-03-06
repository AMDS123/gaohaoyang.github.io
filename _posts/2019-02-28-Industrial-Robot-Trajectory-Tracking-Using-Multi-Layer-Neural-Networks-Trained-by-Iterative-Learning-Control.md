---
layout: post
title: "Industrial Robot Trajectory Tracking Using Multi-Layer Neural Networks Trained by Iterative Learning Control"
date: 2019-02-28 21:57:30
categories: arXiv_RO
tags: arXiv_RO Tracking Transfer_Learning
author: Shuyang Chen, John T. Wen
mathjax: true
---

* content
{:toc}

##### Abstract
Fast and precise robot motion is needed in certain applications such as electronic manufacturing, additive manufacturing and assembly. Most industrial robot motion controllers allow externally commanded motion profile, but the trajectory tracking performance is affected by the robot dynamics and joint servo controllers which users have no direct access and little information. The performance is further compromised by time delays in transmitting the external command as a setpoint to the inner control loop. This paper presents an approach of combining neural networks and iterative learning control to improve the trajectory tracking performance for a multi-axis articulated industrial robot. For a given desired trajectory, the external command is iteratively refined using a high fidelity dynamical simulator to compensate for the robot inner loop dynamics. These desired trajectories and the corresponding refined input trajectories are then used to train multi-layer neural networks to emulate the dynamical inverse of the nonlinear inner loop dynamics. We show that with a sufficiently rich training set, the trained neural networks can generalize well to trajectories beyond the training set. In applying the trained neural networks to the physical robot, the tracking performance still improves but not as much as in the simulator. We show that transfer learning can effectively bridge the gap between simulation and the physical robot. In the end, we test the trained neural networks on other robot models in simulation and demonstrate the possibility of a general purpose network. Development and evaluation of this methodology is based on the ABB IRB6640-180 industrial robot and ABB RobotStudio software packages.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.00082](http://arxiv.org/abs/1903.00082)

##### PDF
[http://arxiv.org/pdf/1903.00082](http://arxiv.org/pdf/1903.00082)

