---
layout: post
title: "Learning to Authenticate with Deep Multibiometric Hashing and Neural Network Decoding"
date: 2019-02-11 21:08:10
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Veeru Talreja, Sobhan Soleymani, Matthew C. Valenti, Nasser M. Nasrabadi
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel three-stage multimodal deep hashing neural decoder (MDHND) architecture, which integrates a deep hashing framework with a neural network decoder (NND) to create an effective multibiometric authentication system. The MDHND consists of two separate modules: a multimodal deep hashing (MDH) module, which is used for feature-level fusion and binarization of multiple biometrics, and a neural network decoder (NND) module, which is used to refine the intermediate binary codes generated by the MDH and compensate for the difference between enrollment and probe biometrics (variations in pose, illumination, etc.). Use of NND helps to improve the performance of the overall multimodal authentication system. The MDHND framework is trained in 3 stages using joint optimization of the two modules. In Stage 1, the MDH parameters are trained and learned to generate a shared multimodal latent code; in Stage 2, the latent codes from Stage 1 are passed through a conventional error-correcting code (ECC) decoder to generate the ground truth to train a neural network decoder (NND); in Stage 3, the NND decoder is trained using the ground truth from Stage 2 and the MDH and NND are jointly optimized. Experimental results on a standard multimodal dataset demonstrate the superiority of our method relative to other current multimodal authentication systems. Furthermore, the proposed system can work in both identification and authentication modes.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.04149](http://arxiv.org/abs/1902.04149)

##### PDF
[http://arxiv.org/pdf/1902.04149](http://arxiv.org/pdf/1902.04149)

