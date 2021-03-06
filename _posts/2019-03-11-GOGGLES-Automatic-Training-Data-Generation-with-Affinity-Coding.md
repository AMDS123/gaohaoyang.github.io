---
layout: post
title: "GOGGLES: Automatic Training Data Generation with Affinity Coding"
date: 2019-03-11 19:19:30
categories: arXiv_CV
tags: arXiv_CV CNN Inference
author: Nilaksh Das, Sanya Chaba, Sakshi Gandhi, Duen Horng Chau, Xu Chu
mathjax: true
---

* content
{:toc}

##### Abstract
Generating large labeled training data is becoming the biggest bottleneck in building and deploying supervised machine learning models. Recently, data programming has been proposed in the data management community to reduce the human cost in training data generation. Data programming expects users to write a set of labeling functions, each of which is a weak supervision source that labels a subset of data points with better-than-random accuracy. However, the success of data programming heavily depends on the quality (in terms of both accuracy and coverage) of the labeling functions that users still need to design manually. 
 We propose affinity coding, a new paradigm for fully automatic generation of training data. In affinity coding, the similarity between the unlabeled instances and prototypes that are derived from the same unlabeled instances serve as signals (or sources of weak supervision) for determining class membership. We term this implicit similarity as the affinity score. Consequently, we can have as many sources of weak supervision as the number of unlabeled data points, without any human input. We also propose a system called GOGGLES that is an implementation of affinity coding for labeling image datasets. GOGGLES features novel techniques for deriving affinity scores from image datasets based on "semantic prototypes" extracted from convolutional neural nets, as well as an expectation-maximization approach for performing class label inference based on the computed affinity scores. 
 Compared to the state-of-the-art data programming system Snorkel, GOGGLES exhibits 14.88% average improvement in terms of the quality of labels generated for the binary labeling task. The GOGGLES system is open-sourced at https://github.com/chu-data-lab/GOGGLES/.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.04552](http://arxiv.org/abs/1903.04552)

##### PDF
[http://arxiv.org/pdf/1903.04552](http://arxiv.org/pdf/1903.04552)

