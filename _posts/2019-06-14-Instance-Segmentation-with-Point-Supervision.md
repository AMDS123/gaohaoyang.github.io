---
layout: post
title: "Instance Segmentation with Point Supervision"
date: 2019-06-14 20:29:38
categories: arXiv_CV
tags: arXiv_CV Segmentation Embedding
author: Issam H. Laradji, Negar Rostamzadeh, Pedro O. Pinheiro, David Vazquez, Mark Schmidt
mathjax: true
---

* content
{:toc}

##### Abstract
Instance segmentation methods often require costly per-pixel labels. We propose a method that only requires point-level annotations. During training, the model only has access to a single pixel label per object, yet the task is to output full segmentation masks. To address this challenge, we construct a network with two branches: (1) a localization network (L-Net) that predicts the location of each object; and (2) an embedding network (E-Net) that learns an embedding space where pixels of the same object are close. The segmentation masks for the located objects are obtained by grouping pixels with similar embeddings. At training time, while L-Net only requires point-level annotations, E-Net uses pseudo-labels generated by a class-agnostic object proposal method. We evaluate our approach on PASCAL VOC, COCO, KITTI and CityScapes datasets. The experiments show that our method (1) obtains competitive results compared to fully-supervised methods in certain scenarios; (2) outperforms fully- and weakly- supervised methods with a fixed annotation budget; and (3) is a first strong baseline for instance segmentation with point-level supervision.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.06392](http://arxiv.org/abs/1906.06392)

##### PDF
[http://arxiv.org/pdf/1906.06392](http://arxiv.org/pdf/1906.06392)
