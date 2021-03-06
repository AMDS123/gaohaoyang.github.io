---
layout: post
title: "Curriculum Learning for Deep Generative Models with Clustering"
date: 2019-06-27 12:44:09
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Face
author: Deli Zhao, Jiapeng Zhu, Zhenfang Guo, Bo Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Training generative models like generative adversarial networks (GANs) and normalizing flows is challenging for noisy data. A novel curriculum learning algorithm pertaining to clustering is proposed to address this issue in this paper. The curriculum construction is based on the centrality of underlying clusters in data points. The data points of high centrality takes priority of being fed into generative models during training. To make our algorithm scalable to large-scale data, the active set is devised, in the sense that every round of training proceeds only on an active subset containing a small fraction of already trained data and the incremental data of lower centrality. Moreover, the geometric analysis is presented to interpret the necessity of cluster curriculum for generative models. The experiments on cat and human-face data validate that our algorithm is able to learn the optimal generative models (e.g. ProGAN and Glow) with respect to specified quality metrics for noisy data. An interesting finding is that the optimal cluster curriculum is closely related to the critical point of a geometric percolation process formulated in the paper.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.11594](http://arxiv.org/abs/1906.11594)

##### PDF
[http://arxiv.org/pdf/1906.11594](http://arxiv.org/pdf/1906.11594)

