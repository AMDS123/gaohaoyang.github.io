---
layout: post
title: "Fine-Grained Age Estimation in the wild with Attention LSTM Networks"
date: 2019-08-15 11:47:05
categories: arXiv_CV
tags: arXiv_CV Attention Face CNN RNN Classification Prediction
author: Ke Zhang, Na Liu, Xingfang Yuan, Xinyao Guo, Ce Gao, Zhenbing Zhao, Zhanyu Ma
mathjax: true
---

* content
{:toc}

##### Abstract
Age estimation from a single face image has been an essential task in the field of human-computer interaction and computer vision, which has a wide range of practical application values. Accuracy of age estimation of face images in the wild is relatively low for existing methods, because they only take into account the global features, while neglecting the fine-grained features of age-sensitive areas. We propose a novel method based on our attention long short-term memory (AL) network for fine-grained age estimation in the wild, inspired by the fine-grained categories and the visual attention mechanism. This method combines the residual networks (ResNets) or the residual network of residual network (RoR) models with LSTM units to construct AL-ResNets or AL-RoR networks to extract local features of age-sensitive regions, which effectively improves the age estimation accuracy. First, a ResNets or a RoR model pretrained on ImageNet dataset is selected as the basic model, which is then fine-tuned on the IMDB-WIKI-101 dataset for age estimation. Then, we fine-tune the ResNets or the RoR on the target age datasets to extract the global features of face images. To extract the local features of age-sensitive regions, the LSTM unit is then presented to obtain the coordinates of the agesensitive region automatically. Finally, the age group classification is conducted directly on the Adience dataset, and age-regression experiments are performed by the Deep EXpectation algorithm (DEX) on MORPH Album 2, FG-NET and 15/16LAP datasets. By combining the global and the local features, we obtain our final prediction results. Experimental results illustrate the effectiveness and robustness of the proposed AL-ResNets or AL-RoR for age estimation in the wild, where it achieves better state-of-the-art performance than all other convolutional neural network.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.10445](http://arxiv.org/abs/1805.10445)

##### PDF
[http://arxiv.org/pdf/1805.10445](http://arxiv.org/pdf/1805.10445)

