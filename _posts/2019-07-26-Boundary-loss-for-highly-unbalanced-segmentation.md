---
layout: post
title: "Boundary loss for highly unbalanced segmentation"
date: 2019-07-26 13:08:27
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Optimization
author: Hoel Kervadec, Jihene Bouchtiba, Christian Desrosiers, &#xc9;ric Granger, Jose Dolz, Ismail Ben Ayed
mathjax: true
---

* content
{:toc}

##### Abstract
Widely used loss functions for convolutional neural network (CNN) segmentation, e.g., Dice or cross-entropy, are based on integrals (summations) over the segmentation regions. Unfortunately, it is quite common in medical image analysis to have highly unbalanced segmentations, where standard losses contain regional terms with values that differ considerably --typically of several orders of magnitude-- across segmentation classes, which may affect training performance and stability. The purpose of this study is to build a boundary loss, which takes the form of a distance metric on the space of contours, not regions. We argue that a boundary loss can mitigate the difficulties of regional losses in the context of highly unbalanced segmentation problems because it uses integrals over the boundary between regions instead of unbalanced integrals over regions. Furthermore, a boundary loss provides information that is complementary to regional losses. Unfortunately, it is not straightforward to represent the boundary points corresponding to the regional softmax outputs of a CNN. Our boundary loss is inspired by discrete (graph-based) optimization techniques for computing gradient flows of curve evolution. Following an integral approach for computing boundary variations, we express a non-symmetric L2 distance on the space of shapes as a regional integral, which avoids completely local differential computations involving contour points. Our boundary loss is the sum of linear functions of the regional softmax probability outputs of the network. Therefore, it can easily be combined with standard regional losses and implemented with any existing deep network architecture for N-D segmentation. Our boundary loss has been validated on two benchmark datasets corresponding to difficult, highly unbalanced segmentation problems: the ischemic stroke lesion (ISLES) and white matter hyperintensities (WMH).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.07032](http://arxiv.org/abs/1812.07032)

##### PDF
[http://arxiv.org/pdf/1812.07032](http://arxiv.org/pdf/1812.07032)

