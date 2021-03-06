---
layout: post
title: "{alpha}-Rank: Multi-Agent Evaluation by Evolution"
date: 2019-03-04 17:13:40
categories: arXiv_AI
tags: arXiv_AI
author: Shayegan Omidshafiei, Christos Papadimitriou, Georgios Piliouras, Karl Tuyls, Mark Rowland, Jean-Baptiste Lespiau, Wojciech M. Czarnecki, Marc Lanctot, Julien Perolat, Remi Munos
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce {\alpha}-Rank, a principled evolutionary dynamics methodology, for the evaluation and ranking of agents in large-scale multi-agent interactions, grounded in a novel dynamical game-theoretic solution concept called Markov-Conley chains (MCCs). The approach leverages continuous-time and discrete-time evolutionary dynamical systems applied to empirical games, and scales tractably in the number of agents, in the type of interactions (beyond dyadic), and the type of empirical games (symmetric and asymmetric). Current models are fundamentally limited in one or more of these dimensions, and are not guaranteed to converge to the desired game-theoretic solution concept (typically the Nash equilibrium). {\alpha}-Rank automatically provides a ranking over the set of agents under evaluation and provides insights into their strengths, weaknesses, and long-term dynamics in terms of basins of attraction and sink components. This is a direct consequence of our new model's direct correspondence to the dynamical MCC solution concept when its ranking-intensity parameter, {\alpha}, is chosen to be large, which exactly forms the basis of {\alpha}-Rank. In contrast to the Nash equilibrium, which is a static solution concept based solely on fixed points, MCCs are a dynamical solution concept based on the Markov chain formalism, Conley's Fundamental Theorem of Dynamical Systems, and the core ingredients of dynamical systems: fixed points, recurrent sets, periodic orbits, and limit cycles. Our {\alpha}-Rank method runs in polynomial time with respect to the total number of pure strategy profiles, whereas computing a Nash equilibrium for a general-sum game is known to be intractable. We introduce mathematical proofs that reveal the formal underpinnings of the {\alpha}-Rank methodology. We illustrate the method in canonical games and in AlphaGo, AlphaZero, MuJoCo Soccer, and Poker.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.01373](http://arxiv.org/abs/1903.01373)

##### PDF
[http://arxiv.org/pdf/1903.01373](http://arxiv.org/pdf/1903.01373)

