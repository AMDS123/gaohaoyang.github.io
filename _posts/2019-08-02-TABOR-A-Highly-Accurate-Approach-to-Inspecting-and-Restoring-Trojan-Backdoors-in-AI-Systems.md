---
layout: post
title: "TABOR: A Highly Accurate Approach to Inspecting and Restoring Trojan Backdoors in AI Systems"
date: 2019-08-02 22:46:03
categories: arXiv_AI
tags: arXiv_AI Optimization Detection
author: Wenbo Guo, Lun Wang, Xinyu Xing, Min Du, Dawn Song
mathjax: true
---

* content
{:toc}

##### Abstract
A trojan backdoor is a hidden pattern typically implanted in a deep neural network. It could be activated and thus forces that infected model behaving abnormally only when an input data sample with a particular trigger present is fed to that model. As such, given a deep neural network model and clean input samples, it is very challenging to inspect and determine the existence of a trojan backdoor. Recently, researchers design and develop several pioneering solutions to address this acute problem. They demonstrate the proposed techniques have a great potential in trojan detection. However, we show that none of these existing techniques completely address the problem. On the one hand, they mostly work under an unrealistic assumption (e.g. assuming availability of the contaminated training database). On the other hand, the proposed techniques cannot accurately detect the existence of trojan backdoors, nor restore high-fidelity trojan backdoor images, especially when the triggers pertaining to the trojan vary in size, shape and position. In this work, we propose TABOR, a new trojan detection technique. Conceptually, it formalizes a trojan detection task as a non-convex optimization problem, and the detection of a trojan backdoor as the task of resolving the optimization through an objective function. Different from the existing technique also modeling trojan detection as an optimization problem, TABOR designs a new objective function--under the guidance of explainable AI techniques as well as heuristics--that could guide optimization to identify a trojan backdoor in a more effective fashion. In addition, TABOR defines a new metric to measure the quality of a trojan backdoor identified. Using an anomaly detection method, we show the new metric could better facilitate TABOR to identify intentionally injected triggers in an infected model and filter out false alarms......

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.01763](http://arxiv.org/abs/1908.01763)

##### PDF
[http://arxiv.org/pdf/1908.01763](http://arxiv.org/pdf/1908.01763)

