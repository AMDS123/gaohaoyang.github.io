---
layout: post
title: "Black-box Adversarial Attacks on Video Recognition Models"
date: 2019-04-10 13:41:02
categories: arXiv_CV
tags: arXiv_CV Adversarial Classification Recognition
author: Linxi Jiang, Xingjun Ma, Shaoxiang Chen, James Bailey, Yu-Gang Jiang
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks (DNNs) are known for their vulnerability to adversarial examples. These are examples that have undergone a small, carefully crafted perturbation, and which can easily fool a DNN into making misclassifications at test time. Thus far, the field of adversarial research has mainly focused on image models, under either a white-box setting, where an adversary has full access to model parameters, or a black-box setting where an adversary can only query the target model for probabilities or labels. Whilst several white-box attacks have been proposed for video models, black-box video attacks are still unexplored. To close this gap, we propose the first black-box video attack framework, called V-BAD. V-BAD is a general framework for adversarial gradient estimation and rectification, based on Natural Evolution Strategies (NES). In particular, V-BAD utilizes \textit{tentative perturbations} transferred from image models, and \textit{partition-based rectifications} found by the NES on partitions (patches) of tentative perturbations, to obtain good adversarial gradient estimates with fewer queries to the target model. V-BAD is equivalent to estimating the projection of an adversarial gradient on a selected subspace. Using three benchmark video datasets, we demonstrate that V-BAD can craft both untargeted and targeted attacks to fool two state-of-the-art deep video recognition models. For the targeted attack, it achieves $&gt;$93\% success rate using only an average of $3.4 \sim 8.4 \times 10^4$ queries, a similar number of queries to state-of-the-art black-box image attacks. This is despite the fact that videos often have two orders of magnitude higher dimensionality than static images. We believe that V-BAD is a promising new tool to evaluate and improve the robustness of video recognition models to black-box adversarial attacks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.05181](http://arxiv.org/abs/1904.05181)

##### PDF
[http://arxiv.org/pdf/1904.05181](http://arxiv.org/pdf/1904.05181)

