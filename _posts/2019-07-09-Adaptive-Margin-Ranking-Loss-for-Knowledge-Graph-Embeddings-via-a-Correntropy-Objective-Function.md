---
layout: post
title: "Adaptive Margin Ranking Loss for Knowledge Graph Embeddings via a Correntropy Objective Function"
date: 2019-07-09 12:32:40
categories: arXiv_AI
tags: arXiv_AI Knowledge_Graph Knowledge Attention Embedding Prediction Relation
author: Mojtaba Nayyeri, Xiaotian Zhou, Sahar Vahdati, Hamed Shariat Yazdi, Jens Lehmann
mathjax: true
---

* content
{:toc}

##### Abstract
Translation-based embedding models have gained significant attention in link prediction tasks for knowledge graphs. TransE is the primary model among translation-based embeddings and is well-known for its low complexity and high efficiency. Therefore, most of the earlier works have modified the score function of the TransE approach in order to improve the performance of link prediction tasks. Nevertheless, proven theoretically and experimentally, the performance of TransE strongly depends on the loss function. Margin Ranking Loss (MRL) has been one of the earlier loss functions which is widely used for training TransE. However, the scores of positive triples are not necessarily enforced to be sufficiently small to fulfill the translation from head to tail by using relation vector (original assumption of TransE). To tackle this problem, several loss functions have been proposed recently by adding upper bounds and lower bounds to the scores of positive and negative samples. Although highly effective, previously developed models suffer from an expansion in search space for a selection of the hyperparameters (in particular the upper and lower bounds of scores) on which the performance of the translation-based models is highly dependent. In this paper, we propose a new loss function dubbed Adaptive Margin Loss (AML) for training translation-based embedding models. The formulation of the proposed loss function enables an adaptive and automated adjustment of the margin during the learning process. Therefore, instead of obtaining two values (upper bound and lower bound), only the center of a margin needs to be determined. During learning, the margin is expanded automatically until it converges. In our experiments on a set of standard benchmark datasets including Freebase and WordNet, the effectiveness of AML is confirmed for training TransE on link prediction tasks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.05336](http://arxiv.org/abs/1907.05336)

##### PDF
[http://arxiv.org/pdf/1907.05336](http://arxiv.org/pdf/1907.05336)

