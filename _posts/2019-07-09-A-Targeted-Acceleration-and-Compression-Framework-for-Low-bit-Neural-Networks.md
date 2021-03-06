---
layout: post
title: "A Targeted Acceleration and Compression Framework for Low bit Neural Networks"
date: 2019-07-09 04:09:55
categories: arXiv_CV
tags: arXiv_CV Attention CNN
author: Biao Qian, Yang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
1 bit deep neural networks (DNNs), of which both the activations and weights are binarized , are attracting more and more attention due to their high computational efficiency and low memory requirement . However, the drawback of large accuracy dropping also restrict s its application. In this paper, we propose a novel Targeted Acceleration and Compression (TAC) framework to improve the performance of 1 bit deep neural networks W e consider that the acceleration and compression effects of binarizing fully connected layer s are not sufficient to compensate for the accuracy loss caused by it In the proposed framework, t he convolutional and fully connected layer are separated and optimized i ndividually . F or the convolutional layer s , both the activations and weights are binarized. For the fully connected layer s, the binarization operation is re placed by network pruning and low bit quantization. The proposed framework is implemented on the CIFAR 10, CIFAR 100 and ImageNet ( ILSVRC 12 ) datasets , and experimental results show that the proposed TAC can significantly improve the accuracy of 1 bit deep neural networks and outperforms the state of the art by more than 6 percentage points .

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.05271](http://arxiv.org/abs/1907.05271)

##### PDF
[http://arxiv.org/pdf/1907.05271](http://arxiv.org/pdf/1907.05271)

