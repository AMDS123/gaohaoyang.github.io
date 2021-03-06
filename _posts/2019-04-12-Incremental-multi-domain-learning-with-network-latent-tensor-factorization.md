---
layout: post
title: "Incremental multi-domain learning with network latent tensor factorization"
date: 2019-04-12 17:57:05
categories: arXiv_AI
tags: arXiv_AI Knowledge Classification Deep_Learning Relation
author: Adrian Bulat, Jean Kossaifi, Georgios Tzimiropoulos, Maja Pantic
mathjax: true
---

* content
{:toc}

##### Abstract
The prominence of deep learning, large amount of annotated data and increasingly powerful hardware made it possible to reach remarkable performance for supervised classification tasks, in many cases saturating the training sets. However, adapting the learned classification to new domains remains a hard problem due to at least three reasons: (1) the domains and the tasks might be drastically different; (2) there might be very limited amount of annotated data on the new domain and (3) full training of a new model for each new task is prohibitive in terms of memory, due to the shear number of parameter of deep networks. Instead, new tasks should be learned incrementally, building on prior knowledge from already learned tasks, and without catastrophic forgetting, i.e. without hurting performance on prior tasks. To our knowledge this paper presents the first method for multi-domain/task learning without catastrophic forgetting using a fully tensorized architecture. Our main contribution is a method for multi-domain learning which models groups of identically structured blocks within a CNN as a high-order tensor. We show that this joint modelling naturally leverages correlations across different layers and results in more compact representations for each new task/domain over previous methods which have focused on adapting each layer separately. We apply the proposed method to 10 datasets of the Visual Decathlon Challenge and show that our method offers on average about 7.5x reduction in number of parameters and superior performance in terms of both classification accuracy and Decathlon score. In particular, our method outperforms all prior work on the Visual Decathlon Challenge.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.06345](http://arxiv.org/abs/1904.06345)

##### PDF
[http://arxiv.org/pdf/1904.06345](http://arxiv.org/pdf/1904.06345)

