---
layout: post
title: "Dynamic Planning Networks"
date: 2019-02-04 15:15:44
categories: arXiv_CV
tags: arXiv_CV Reinforcement_Learning
author: Norman Tasfi, Miriam Capretz
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce Dynamic Planning Networks (DPN), a novel architecture for deep reinforcement learning, that combines model-based and model-free aspects for online planning. Our architecture learns to dynamically construct plans using a learned state-transition model by selecting and traversing between simulated states and actions to maximize information before acting. In contrast to model-free methods, model-based planning lets the agent efficiently test action hypotheses without performing costly trial-and-error in the environment. DPN learns to efficiently form plans by expanding a single action-conditional state transition at a time instead of exhaustively evaluating each action, reducing the required number of state-transitions during planning by up to 96%. We observe various emergent planning patterns used to solve environments, including classical search methods such as breadth-first and depth-first search. DPN shows improved data efficiency, performance, and generalization to new and unseen domains in comparison to several baselines.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1812.11240](https://arxiv.org/abs/1812.11240)

##### PDF
[https://arxiv.org/pdf/1812.11240](https://arxiv.org/pdf/1812.11240)

