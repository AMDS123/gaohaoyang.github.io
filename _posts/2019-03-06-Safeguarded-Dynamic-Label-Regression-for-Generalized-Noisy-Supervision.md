---
layout: post
title: "Safeguarded Dynamic Label Regression for Generalized Noisy Supervision"
date: 2019-03-06 03:20:09
categories: arXiv_CV
tags: arXiv_CV
author: Jiangchao Yao, Ya Zhang, Ivor W. Tsang, Jun Sun
mathjax: true
---

* content
{:toc}

##### Abstract
Learning with noisy labels, which aims to reduce expensive labors on accurate annotations, has become imperative in the Big Data era. Previous noise transition based method has achieved promising results and presented a theoretical guarantee on performance in the case of class-conditional noise. However, this type of approaches critically depend on an accurate pre-estimation of the noise transition, which is usually impractical. Subsequent improvement adapts the pre-estimation along with the training progress via a Softmax layer. However, the parameters in the Softmax layer are highly tweaked for the fragile performance due to the ill-posed stochastic approximation. To address these issues, we propose a Latent Class-Conditional Noise model (LCCN) that naturally embeds the noise transition under a Bayesian framework. By projecting the noise transition into a Dirichlet-distributed space, the learning is constrained on a simplex based on the whole dataset, instead of some ad-hoc parametric space. We then deduce a dynamic label regression method for LCCN to iteratively infer the latent labels, to stochastically train the classifier and to model the noise. Our approach safeguards the bounded update of the noise transition, which avoids previous arbitrarily tuning via a batch of samples. We further generalize LCCN for open-set noisy labels and the semi-supervised setting. We perform extensive experiments with the controllable noise data sets, CIFAR-10 and CIFAR-100, and the agnostic noise data sets, Clothing1M and WebVision17. The experimental results have demonstrated that the proposed model outperforms several state-of-the-art methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.02152](http://arxiv.org/abs/1903.02152)

##### PDF
[http://arxiv.org/pdf/1903.02152](http://arxiv.org/pdf/1903.02152)

