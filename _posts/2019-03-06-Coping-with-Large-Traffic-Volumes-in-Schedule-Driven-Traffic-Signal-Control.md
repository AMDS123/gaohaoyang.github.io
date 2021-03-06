---
layout: post
title: "Coping with Large Traffic Volumes in Schedule-Driven Traffic Signal Control"
date: 2019-03-06 19:42:36
categories: arXiv_AI
tags: arXiv_AI
author: Hsu-Chieh Hu, Stephen F. Smith
mathjax: true
---

* content
{:toc}

##### Abstract
Recent work in decentralized, schedule-driven traffic control has demonstrated the ability to significantly improve traffic flow efficiency in complex urban road networks. However, in situations where vehicle volumes increase to the point that the physical capacity of a road network reaches or exceeds saturation, it has been observed that the effectiveness of a schedule-driven approach begins to degrade, leading to progressively higher network congestion. In essence, the traffic control problem becomes less of a scheduling problem and more of a queue management problem in this circumstance. In this paper we propose a composite approach to real-time traffic control that uses sensed information on queue lengths to influence scheduling decisions and gracefully shift the signal control strategy to queue management in high volume/high congestion settings. Specifically, queue-length information is used to establish weights for the sensed vehicle clusters that must be scheduled through a given intersection at any point, and hence bias the wait time minimization calculation. To compute these weights, we develop a model in which successive movement phases are viewed as different states of an Ising model, and parameters quantify strength of interactions. To ensure scalability, queue information is only exchanged between direct neighbors and the asynchronous nature of local intersection scheduling is preserved. We demonstrate the potential of the approach through microscopic traffic simulation of a real-world road network, showing a 60% reduction in average wait times over the baseline schedule-driven approach in heavy traffic scenarios. We also report initial field test results, which show the ability to reduce queues during heavy traffic periods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.04278](http://arxiv.org/abs/1903.04278)

##### PDF
[http://arxiv.org/pdf/1903.04278](http://arxiv.org/pdf/1903.04278)

