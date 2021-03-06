---
layout: post
title: "Contrast-Oriented Deep Neural Networks for Salient Object Detection"
date: 2018-03-30 09:51:04
categories: arXiv_CV
tags: arXiv_CV Salient Object_Detection Sparse Attention Embedding CNN Inference Prediction Detection
author: Guanbin Li, Yizhou Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional neural networks have become a key element in the recent breakthrough of salient object detection. However, existing CNN-based methods are based on either patch-wise (region-wise) training and inference or fully convolutional networks. Methods in the former category are generally time-consuming due to severe storage and computational redundancies among overlapping patches. To overcome this deficiency, methods in the second category attempt to directly map a raw input image to a predicted dense saliency map in a single network forward pass. Though being very efficient, it is arduous for these methods to detect salient objects of different scales or salient regions with weak semantic information. In this paper, we develop hybrid contrast-oriented deep neural networks to overcome the aforementioned limitations. Each of our deep networks is composed of two complementary components, including a fully convolutional stream for dense prediction and a segment-level spatial pooling stream for sparse saliency inference. We further propose an attentional module that learns weight maps for fusing the two saliency predictions from these two streams. A tailored alternate scheme is designed to train these deep networks by fine-tuning pre-trained baseline models. Finally, a customized fully connected CRF model incorporating a salient contour feature embedding can be optionally applied as a post-processing step to improve spatial coherence and contour positioning in the fused result from these two streams. Extensive experiments on six benchmark datasets demonstrate that our proposed model can significantly outperform the state of the art in terms of all popular evaluation metrics.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1803.11395](https://arxiv.org/abs/1803.11395)

##### PDF
[https://arxiv.org/pdf/1803.11395](https://arxiv.org/pdf/1803.11395)

