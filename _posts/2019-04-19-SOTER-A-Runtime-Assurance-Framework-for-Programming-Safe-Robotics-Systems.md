---
layout: post
title: "SOTER: A Runtime Assurance Framework for Programming Safe Robotics Systems"
date: 2019-04-19 19:02:53
categories: arXiv_AI
tags: arXiv_AI Drone
author: Ankush Desai, Shromona Ghosh, Sanjit A. Seshia, Natarajan Shankar, Ashish Tiwari
mathjax: true
---

* content
{:toc}

##### Abstract
The recent drive towards achieving greater autonomy and intelligence in robotics has led to high levels of complexity. Autonomous robots increasingly depend on third party off-the-shelf components and complex machine-learning techniques. This trend makes it challenging to provide strong design-time certification of correct operation. 
 To address these challenges, we present SOTER, a robotics programming framework with two key components: (1) a programming language for implementing and testing high-level reactive robotics software and (2) an integrated runtime assurance (RTA) system that helps enable the use of uncertified components, while still providing safety guarantees. SOTER provides language primitives to declaratively construct a RTA module consisting of an advanced, high-performance controller (uncertified), a safe, lower-performance controller (certified), and the desired safety specification. The framework provides a formal guarantee that a well-formed RTA module always satisfies the safety specification, without completely sacrificing performance by using higher performance uncertified components whenever safe. SOTER allows the complex robotics software stack to be constructed as a composition of RTA modules, where each uncertified component is protected using a RTA module. 
 To demonstrate the efficacy of our framework, we consider a real-world case-study of building a safe drone surveillance system. Our experiments both in simulation and on actual drones show that the SOTER-enabled RTA ensures the safety of the system, including when untrusted third-party components have bugs or deviate from the desired behavior.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1808.07921](http://arxiv.org/abs/1808.07921)

##### PDF
[http://arxiv.org/pdf/1808.07921](http://arxiv.org/pdf/1808.07921)

