---
layout: post
title: "Human-Like Autonomous Car-Following Model with Deep Reinforcement Learning"
date: 2019-01-03 01:05:29
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Meixin Zhu, Xuesong Wang, Yinhai Wang
mathjax: true
---

* content
{:toc}

##### Abstract
This study proposes a framework for human-like autonomous car-following planning based on deep reinforcement learning (deep RL). Historical driving data are fed into a simulation environment where an RL agent learns from trial and error interactions based on a reward function that signals how much the agent deviates from the empirical data. Through these interactions, an optimal policy, or car-following model that maps in a human-like way from speed, relative speed between a lead and following vehicle, and inter-vehicle spacing to acceleration of a following vehicle is finally obtained. The model can be continuously updated when more data are fed in. Two thousand car-following periods extracted from the 2015 Shanghai Naturalistic Driving Study were used to train the model and compare its performance with that of traditional and recent data-driven car-following models. As shown by this study results, a deep deterministic policy gradient car-following model that uses disparity between simulated and observed speed as the reward function and considers a reaction delay of 1s, denoted as DDPGvRT, can reproduce human-like car-following behavior with higher accuracy than traditional and recent data-driven car-following models. Specifically, the DDPGvRT model has a spacing validation error of 18% and speed validation error of 5%, which are less than those of other models, including the intelligent driver model, models based on locally weighted regression, and conventional neural network-based models. Moreover, the DDPGvRT demonstrates good capability of generalization to various driving situations and can adapt to different drivers by continuously learning. This study demonstrates that reinforcement learning methodology can offer insight into driver behavior and can contribute to the development of human-like autonomous driving algorithms and traffic-flow models.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.00569](http://arxiv.org/abs/1901.00569)

##### PDF
[http://arxiv.org/pdf/1901.00569](http://arxiv.org/pdf/1901.00569)

