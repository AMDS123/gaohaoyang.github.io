---
layout: post
title: "Contextualized Spatial-Temporal Network for Taxi Origin-Destination Demand Prediction"
date: 2019-05-15 10:21:05
categories: arXiv_AI
tags: arXiv_AI CNN RNN Prediction Relation
author: Lingbo Liu, Zhilin Qiu, Guanbin Li, Qing Wang, Wanli Ouyang, Liang Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Taxi demand prediction has recently attracted increasing research interest due to its huge potential application in large-scale intelligent transportation systems. However, most of the previous methods only considered the taxi demand prediction in origin regions, but neglected the modeling of the specific situation of the destination passengers. We believe it is suboptimal to preallocate the taxi into each region based solely on the taxi origin demand. In this paper, we present a challenging and worth-exploring task, called taxi origin-destination demand prediction, which aims at predicting the taxi demand between all region pairs in a future time interval. Its main challenges come from how to effectively capture the diverse contextual information to learn the demand patterns. We address this problem with a novel Contextualized Spatial-Temporal Network (CSTN), which consists of three components for the modeling of local spatial context (LSC), temporal evolution context (TEC) and global correlation context (GCC) respectively. Firstly, an LSC module utilizes two convolution neural networks to learn the local spatial dependencies of taxi demand respectively from the origin view and the destination view. Secondly, a TEC module incorporates both the local spatial features of taxi demand and the meteorological information to a Convolutional Long Short-term Memory Network (ConvLSTM) for the analysis of taxi demand evolution. Finally, a GCC module is applied to model the correlation between all regions by computing a global correlation feature as a weighted sum of all regional features, with the weights being calculated as the similarity between the corresponding region pairs. Extensive experiments and evaluations on a large-scale dataset well demonstrate the superiority of our CSTN over other compared methods for taxi origin-destination demand prediction.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.06335](http://arxiv.org/abs/1905.06335)

##### PDF
[http://arxiv.org/pdf/1905.06335](http://arxiv.org/pdf/1905.06335)

