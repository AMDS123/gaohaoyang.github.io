---
layout: post
title: "Deep Hierarchical Reinforcement Learning Based Recommendations via Multi-goals Abstraction"
date: 2019-03-22 06:43:49
categories: arXiv_AI
tags: arXiv_AI Sparse Reinforcement_Learning Recommendation
author: Dongyang Zhao, Liang Zhang, Bo Zhang, Lizhou Zheng, Yongjun Bao, Weipeng Yan
mathjax: true
---

* content
{:toc}

##### Abstract
The recommender system is an important form of intelligent application, which assists users to alleviate from information redundancy. Among the metrics used to evaluate a recommender system, the metric of conversion has become more and more important. The majority of existing recommender systems perform poorly on the metric of conversion due to its extremely sparse feedback signal. To tackle this challenge, we propose a deep hierarchical reinforcement learning based recommendation framework, which consists of two components, i.e., high-level agent and low-level agent. The high-level agent catches long-term sparse conversion signals, and automatically sets abstract goals for low-level agent, while the low-level agent follows the abstract goals and interacts with real-time environment. To solve the inherent problem in hierarchical reinforcement learning, we propose a novel deep hierarchical reinforcement learning algorithm via multi-goals abstraction (HRL-MG). Our proposed algorithm contains three characteristics: 1) the high-level agent generates multiple goals to guide the low-level agent in different stages, which reduces the difficulty of approaching high-level goals; 2) different goals share the same state encoder parameters, which increases the update frequency of the high-level agent and thus accelerates the convergence of our proposed algorithm; 3) an appreciate benefit assignment function is designed to allocate rewards in each goal so as to coordinate different goals in a consistent direction. We evaluate our proposed algorithm based on a real-world e-commerce dataset and validate its effectiveness.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.09374](http://arxiv.org/abs/1903.09374)

##### PDF
[http://arxiv.org/pdf/1903.09374](http://arxiv.org/pdf/1903.09374)

