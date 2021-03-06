---
layout: post
title: "Deep Reference Generation with Multi-Domain Hierarchical Constraints for Inter Prediction"
date: 2019-05-16 07:23:20
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Prediction
author: Jiaying Liu, Sifeng Xia, Wenhan Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Inter prediction is an important module in video coding for temporal redundancy removal, where similar reference blocks are searched from previously coded frames and employed to predict the block to be coded. Although traditional video codecs can estimate and compensate for block-level motions, their inter prediction performance is still heavily affected by the remaining inconsistent pixel-wise displacement caused by irregular rotation and deformation. In this paper, we address the problem by proposing a deep frame interpolation network to generate additional reference frames in coding scenarios. First, we summarize the previous adaptive convolutions used for frame interpolation and propose a factorized kernel convolutional network to improve the modeling capacity and simultaneously keep its compact form. Second, to better train this network, multi-domain hierarchical constraints are introduced to regularize the training of our factorized kernel convolutional network. For spatial domain, we use a gradually down-sampled and up-sampled auto-encoder to generate the factorized kernels for frame interpolation at different scales. For quality domain, considering the inconsistent quality of the input frames, the factorized kernel convolution is modulated with quality-related features to learn to exploit more information from high quality frames. For frequency domain, a sum of absolute transformed difference loss that performs frequency transformation is utilized to facilitate network optimization from the view of coding performance. With the well-designed frame interpolation network regularized by multi-domain hierarchical constraints, our method surpasses HEVC on average 6.1% BD-rate saving and up to 11.0% BD-rate saving for the luma component under the random access configuration.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.06567](http://arxiv.org/abs/1905.06567)

##### PDF
[http://arxiv.org/pdf/1905.06567](http://arxiv.org/pdf/1905.06567)

