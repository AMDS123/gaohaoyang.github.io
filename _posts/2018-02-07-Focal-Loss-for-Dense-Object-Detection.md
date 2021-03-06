---
layout: post
title: "Focal Loss for Dense Object Detection"
date: 2018-02-07 18:44:44
categories: arXiv_CV
tags: arXiv_CV Object_Detection Sparse Detection
author: Tsung-Yi Lin, Priya Goyal, Ross Girshick, Kaiming He, Piotr Dollár
mathjax: true
---

* content
{:toc}

##### Abstract
The highest accuracy object detectors to date are based on a two-stage approach popularized by R-CNN, where a classifier is applied to a sparse set of candidate object locations. In contrast, one-stage detectors that are applied over a regular, dense sampling of possible object locations have the potential to be faster and simpler, but have trailed the accuracy of two-stage detectors thus far. In this paper, we investigate why this is the case. We discover that the extreme foreground-background class imbalance encountered during training of dense detectors is the central cause. We propose to address this class imbalance by reshaping the standard cross entropy loss such that it down-weights the loss assigned to well-classified examples. Our novel Focal Loss focuses training on a sparse set of hard examples and prevents the vast number of easy negatives from overwhelming the detector during training. To evaluate the effectiveness of our loss, we design and train a simple dense detector we call RetinaNet. Our results show that when trained with the focal loss, RetinaNet is able to match the speed of previous one-stage detectors while surpassing the accuracy of all existing state-of-the-art two-stage detectors. Code is at: this https URL.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1708.02002](https://arxiv.org/abs/1708.02002)

##### PDF
[https://arxiv.org/pdf/1708.02002](https://arxiv.org/pdf/1708.02002)

