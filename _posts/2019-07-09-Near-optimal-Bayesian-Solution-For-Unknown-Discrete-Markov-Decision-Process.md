---
layout: post
title: "Near-optimal Bayesian Solution For Unknown Discrete Markov Decision Process"
date: 2019-07-09 21:47:50
categories: arXiv_AI
tags: arXiv_AI
author: Aristide Tossou, Christos Dimitrakakis, Debabrota Basu
mathjax: true
---

* content
{:toc}

##### Abstract
We tackle the problem of acting in an unknown finite and discrete Markov Decision Process (MDP) for which the expected shortest path from any state to any other state is bounded by a finite number $D$. An MDP consists of $S$ states and $A$ possible actions per state. Upon choosing an action $a_t$ at state $s_t$, one receives a real value reward $r_t$, then one transits to a next state $s_{t+1}$. The reward $r_t$ is generated from a fixed reward distribution depending only on $(s_t, a_t)$ and similarly, the next state $s_{t+1}$ is generated from a fixed transition distribution depending only on $(s_t, a_t)$. The objective is to maximize the accumulated rewards after $T$ interactions. In this paper, we consider the case where the reward distributions, the transitions, $T$ and $D$ are all unknown. We derive the first polynomial time Bayesian algorithm, BUCRL{} that achieves up to logarithm factors, a regret (i.e the difference between the accumulated rewards of the optimal policy and our algorithm) of the optimal order $\tilde{\mathcal{O}}(\sqrt{DSAT})$. Importantly, our result holds with high probability for the worst-case (frequentist) regret and not the weaker notion of Bayesian regret. We perform experiments in a variety of environments that demonstrate the superiority of our algorithm over previous techniques. 
 Our work also illustrates several results that will be of independent interest. In particular, we derive a sharper upper bound for the KL-divergence of Bernoulli random variables. We also derive sharper upper and lower bounds for Beta and Binomial quantiles. All the bound are very simple and only use elementary functions.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.09114](http://arxiv.org/abs/1906.09114)

##### PDF
[http://arxiv.org/pdf/1906.09114](http://arxiv.org/pdf/1906.09114)

