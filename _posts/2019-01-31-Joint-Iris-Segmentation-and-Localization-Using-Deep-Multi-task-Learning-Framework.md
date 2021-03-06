---
layout: post
title: "Joint Iris Segmentation and Localization Using Deep Multi-task Learning Framework"
date: 2019-01-31 03:16:15
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation Attention CNN Deep_Learning Relation
author: Caiyong Wang, Yuhao Zhu, Yunfan Liu, Ran He, Zhenan Sun
mathjax: true
---

* content
{:toc}

##### Abstract
Iris segmentation and localization in non-cooperative environment is challenging due to illumination variations, long distances, moving subjects and limited user cooperation, etc. Traditional methods often suffer from poor performance when confronted with iris images captured in these conditions. Recent studies have shown that deep learning methods could achieve impressive performance on iris segmentation task. In addition, as iris is defined as an annular region between pupil and sclera, geometric constraints could be imposed to help locating the iris more accurately and improve the segmentation results. In this paper, we propose a deep multi-task learning framework, named as IrisParseNet, to exploit the inherent correlations between pupil, iris and sclera to boost up the performance of iris segmentation and localization in a unified model. In particular, IrisParseNet firstly applies a Fully Convolutional Encoder-Decoder Attention Network to simultaneously estimate pupil center, iris segmentation mask and iris inner/outer boundary. Then, an effective post-processing method is adopted for iris inner/outer circle localization.To train and evaluate the proposed method, we manually label three challenging iris datasets, namely CASIA-Iris-Distance, UBIRIS.v2, and MICHE-I, which cover various types of noises. Extensive experiments are conducted on these newly annotated datasets, and results show that our method outperforms state-of-the-art methods on various benchmarks. All the ground-truth annotations, annotation codes and evaluation protocols are publicly available at https://github.com/xiamenwcy/IrisParseNet.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.11195](http://arxiv.org/abs/1901.11195)

##### PDF
[http://arxiv.org/pdf/1901.11195](http://arxiv.org/pdf/1901.11195)

