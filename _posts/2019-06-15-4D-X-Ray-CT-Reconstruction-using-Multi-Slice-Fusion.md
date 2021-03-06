---
layout: post
title: "4D X-Ray CT Reconstruction using Multi-Slice Fusion"
date: 2019-06-15 18:37:56
categories: arXiv_CV
tags: arXiv_CV CNN
author: Soumendu Majee, Thilo Balke, Craig A. J. Kemp, Gregery T. Buzzard, Charles A. Bouman
mathjax: true
---

* content
{:toc}

##### Abstract
There is an increasing need to reconstruct objects in four or more dimensions corresponding to space, time and other independent parameters. The best 4D reconstruction algorithms use regularized iterative reconstruction approaches such as model based iterative reconstruction (MBIR), which depends critically on the quality of the prior modeling. Recently, Plug-and-Play methods have been shown to be an effective way to incorporate advanced prior models using state-of-the-art denoising algorithms designed to remove additive white Gaussian noise (AWGN). However, state-of-the-art denoising algorithms such as BM4D and deep convolutional neural networks (CNNs) are primarily available for 2D and sometimes 3D images. In particular, CNNs are difficult and computationally expensive to implement in four or more dimensions, and training may be impossible if there is no associated high-dimensional training data. 
 In this paper, we present Multi-Slice Fusion, a novel algorithm for 4D and higher-dimensional reconstruction, based on the fusion of multiple low-dimensional denoisers. Our approach uses multi-agent consensus equilibrium (MACE), an extension of Plug-and-Play, as a framework for integrating the multiple lower-dimensional prior models. We apply our method to the problem of 4D cone-beam X-ray CT reconstruction for Non Destructive Evaluation (NDE) of moving parts. This is done by solving the MACE equations using lower-dimensional CNN denoisers implemented in parallel on a heterogeneous cluster. Results on experimental CT data demonstrate that Multi-Slice Fusion can substantially improve the quality of reconstructions relative to traditional 4D priors, while also being practical to implement and train.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.06601](http://arxiv.org/abs/1906.06601)

##### PDF
[http://arxiv.org/pdf/1906.06601](http://arxiv.org/pdf/1906.06601)

