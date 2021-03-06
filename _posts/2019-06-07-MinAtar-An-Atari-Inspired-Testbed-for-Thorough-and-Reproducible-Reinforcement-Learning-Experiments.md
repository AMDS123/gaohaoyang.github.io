---
layout: post
title: "MinAtar: An Atari-Inspired Testbed for Thorough and Reproducible Reinforcement Learning Experiments"
date: 2019-06-07 00:36:50
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Represenation_Learning
author: Kenny Young, Tian Tian
mathjax: true
---

* content
{:toc}

##### Abstract
The Arcade Learning Environment (ALE) is a popular platform for evaluating reinforcement learning agents. Much of the appeal comes from the fact that Atari games demonstrate aspects of competency we expect from an intelligent agent and are not biased toward any particular solution approach. The challenge of the ALE includes (1) the representation learning problem of extracting pertinent information from raw pixels, and (2) the behavioural learning problem of leveraging complex, delayed associations between actions and rewards. Often, the research questions we are interested in pertain more to the latter, but the representation learning problem adds significant computational expense. We introduce MinAtar, short for miniature Atari, a new set of environments that capture the general mechanics of specific Atari games while simplifying the representational complexity to focus more on the behavioural challenges. MinAtar consists of analogues of five Atari games: Seaquest, Breakout, Asterix, Freeway and Space Invaders. Each MinAtar environment provides the agent with a 10x10xn binary state representation. Each game plays out on a 10x10 grid with n channels corresponding to game-specific objects, such as ball, paddle and brick in the game Breakout. To investigate the behavioural challenges posed by MinAtar, we evaluated a smaller version of the DQN architecture as well as online actor-critic with eligibility traces. With the representation learning problem simplified, we can perform experiments with significantly less computational expense. In our experiments, we use the saved compute time to perform step-size parameter sweeps and more runs than is typical for the ALE. Experiments like this improve reproducibility, and allow us to draw more confident conclusions. We hope that MinAtar can allow researchers to thoroughly investigate behavioural challenges similar to those inherent in the ALE.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.03176](http://arxiv.org/abs/1903.03176)

##### PDF
[http://arxiv.org/pdf/1903.03176](http://arxiv.org/pdf/1903.03176)

