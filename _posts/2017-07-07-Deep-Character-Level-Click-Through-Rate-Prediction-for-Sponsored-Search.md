---
layout: post
title: "Deep Character-Level Click-Through Rate Prediction for Sponsored Search"
date: 2017-07-07 13:15:45
categories: arXiv_CV
tags: arXiv_CV CNN Language_Model Prediction
author: Bora Edizel, Amin Mantrach, Xiao Bai
mathjax: true
---

* content
{:toc}

##### Abstract
Predicting the click-through rate of an advertisement is a critical component of online advertising platforms. In sponsored search, the click-through rate estimates the probability that a displayed advertisement is clicked by a user after she submits a query to the search engine. Commercial search engines typically rely on machine learning models trained with a large number of features to make such predictions. This is inevitably requires a lot of engineering efforts to define, compute, and select the appropriate features. In this paper, we propose two novel approaches (one working at character level and the other working at word level) that use deep convolutional neural networks to predict the click-through rate of a query-advertisement pair. Specially, the proposed architectures only consider the textual content appearing in a query-advertisement pair as input, and produce as output a click-through rate prediction. By comparing the character-level model with the word-level model, we show that language representation can be learnt from scratch at character level when trained on enough data. Through extensive experiments using billions of query-advertisement pairs of a popular commercial search engine, we demonstrate that both approaches significantly outperform a baseline model built on well-selected text features and a state-of-the-art word2vec-based approach. Finally, by combining the predictions of the deep models introduced in this study with the prediction of the model in production of the same commercial search engine, we significantly improve the accuracy and the calibration of the click-through rate prediction of the production system.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1707.02158](https://arxiv.org/abs/1707.02158)

##### PDF
[https://arxiv.org/pdf/1707.02158](https://arxiv.org/pdf/1707.02158)

