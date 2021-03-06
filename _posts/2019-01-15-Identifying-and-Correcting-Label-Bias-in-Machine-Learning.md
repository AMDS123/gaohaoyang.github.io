---
layout: post
title: "Identifying and Correcting Label Bias in Machine Learning"
date: 2019-01-15 18:40:06
categories: arXiv_AI
tags: arXiv_AI Classification
author: Heinrich Jiang, Ofir Nachum
mathjax: true
---

* content
{:toc}

##### Abstract
Datasets often contain biases which unfairly disadvantage certain groups, and classifiers trained on such datasets can inherit these biases. In this paper, we provide a mathematical formulation of how this bias can arise. We do so by assuming the existence of underlying, unknown, and unbiased labels which are overwritten by an agent who intends to provide accurate labels but may have biases against certain groups. Despite the fact that we only observe the biased labels, we are able to show that the bias may nevertheless be corrected by re-weighting the data points without changing the labels. We show, with theoretical guarantees, that training on the re-weighted dataset corresponds to training on the unobserved but unbiased labels, thus leading to an unbiased machine learning classifier. Our procedure is fast and robust and can be used with virtually any learning algorithm. We evaluate on a number of standard machine learning fairness datasets and a variety of fairness notions, finding that our method outperforms standard approaches in achieving fair classification.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1901.04966](https://arxiv.org/abs/1901.04966)

##### PDF
[https://arxiv.org/pdf/1901.04966](https://arxiv.org/pdf/1901.04966)

