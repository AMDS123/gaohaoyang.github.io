---
layout: post
title: "Real-time interactive magnetic resonance temperature imaging in both aqueous and adipose tissues using cascaded deep neural networks for MR-guided focused ultrasound surgery"
date: 2019-08-29 00:33:29
categories: arXiv_CV
tags: arXiv_CV CNN
author: Jong-Min Kim, You-Jin Jeong, Han-Jae Chung, Chulhyun Lee, Chang-Hyun Oh
mathjax: true
---

* content
{:toc}

##### Abstract
Purpose: To acquire the real-time interactive temperature map for aqueous and adipose tissue, the problems of long acquisition and processing time must be addressed. To overcome these major challenges, this paper proposes a cascaded convolutional neural network (CNN) framework and multi-echo gradient echo (meGRE) with a single reference variable flip angle (srVFA). 
 Methods: To optimize the echo times for each method, MR images are acquired using a meGRE sequence; meGRE images with two flip angles (FAs) and meGRE images with a single FA are acquired during the pretreatment and treatment stages, respectively. These images are then processed and reconstructed by a cascaded CNN, which consists of two CNNs. The first CNN (called DeepACCnet) performs HR complex MR image reconstruction from the LR MR image acquired during the treatment stage, which is improved by the HR magnitude MR image acquired during the pretreatment stage. The second CNN (called DeepPROCnet) copes with T1 mapping. 
 Results: Measurements of temperature and T1 changes obtained by meGRE combined with srVFA and cascaded CNNs were achieved in an agarose gel phantom, ex vivo porcine muscle, and ex vivo porcine muscle with fat layers (heating tests), and in vivo human prostate and brain (non-heating tests). In the heating test, the maximum differences between fiber-optic sensor and samples are less than 1 degree Celcius. In all cases, temperature mapping using the cascaded CNN achieved the best results in all cases. The acquisition and processing times for the proposed method are 0.8 s and 32 ms, respectively. 
 Conclusions: Real-time interactive HR MR temperature mapping for simultaneously measuring aqueous and adipose tissue is feasible by combining a cascaded CNN with meGRE and srVFA.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.10995](http://arxiv.org/abs/1908.10995)

##### PDF
[http://arxiv.org/pdf/1908.10995](http://arxiv.org/pdf/1908.10995)

