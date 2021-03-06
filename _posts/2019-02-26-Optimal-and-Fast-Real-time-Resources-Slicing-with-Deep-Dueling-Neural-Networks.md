---
layout: post
title: "Optimal and Fast Real-time Resources Slicing with Deep Dueling Neural Networks"
date: 2019-02-26 01:46:01
categories: arXiv_AI
tags: arXiv_AI Optimization Deep_Learning
author: Nguyen Van Huynh, Dinh Thai Hoang, Diep N. Nguyen, Eryk Dutkiewicz
mathjax: true
---

* content
{:toc}

##### Abstract
Effective network slicing requires an infrastructure/network provider to deal with the uncertain demand and real-time dynamics of network resource requests. Another challenge is the combinatorial optimization of numerous resources, e.g., radio, computing, and storage. This article develops an optimal and fast real-time resource slicing framework that maximizes the long-term return of the network provider while taking into account the uncertainty of resource demand from tenants. Specifically, we first propose a novel system model which enables the network provider to effectively slice various types of resources to different classes of users under separate virtual slices. We then capture the real-time arrival of slice requests by a semi-Markov decision process. To obtain the optimal resource allocation policy under the dynamics of slicing requests, e.g., uncertain service time and resource demands, a Q-learning algorithm is often adopted in the literature. However, such an algorithm is notorious for its slow convergence, especially for problems with large state/action spaces. This makes Q-learning practically inapplicable to our case in which multiple resources are simultaneously optimized. To tackle it, we propose a novel network slicing approach with an advanced deep learning architecture, called deep dueling that attains the optimal average reward much faster than the conventional Q-learning algorithm. This property is especially desirable to cope with real-time resource requests and the dynamic demands of users. Extensive simulations show that the proposed framework yields up to 40% higher long-term average return while being few thousand times faster, compared with state of the art network slicing approaches.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.09696](http://arxiv.org/abs/1902.09696)

##### PDF
[http://arxiv.org/pdf/1902.09696](http://arxiv.org/pdf/1902.09696)

