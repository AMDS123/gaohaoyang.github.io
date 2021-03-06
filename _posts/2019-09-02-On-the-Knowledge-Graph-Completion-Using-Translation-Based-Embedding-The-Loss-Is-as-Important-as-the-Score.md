---
layout: post
title: "On the Knowledge Graph Completion Using Translation Based Embedding: The Loss Is as Important as the Score"
date: 2019-09-02 03:10:14
categories: arXiv_AI
tags: arXiv_AI Knowledge_Graph Knowledge Embedding Relation
author: Mojtaba Nayyeri, Chengjin Xu, Yadollah Yaghoobzadeh, Hamed Shariat Yazdi, Jens Lehmann
mathjax: true
---

* content
{:toc}

##### Abstract
Knowledge graphs (KGs) represent world's facts in structured forms. KG completion exploits the existing facts in a KG to discover new ones. Translation-based embedding model (TransE) is a prominent formulation to do KG completion. Despite the efficiency of TransE in memory and time, it suffers from several limitations in encoding relation patterns such as many-to-many relation patterns, symmetric, reflexive etc. To tackle this problem, most of the attempts have circled around the revision of the score function of TransE i.e., proposing a more complicated score function such as Trans(A, D, G, H, R, etc) to mitigate the limitations. In this paper, we tackle this problem from a different perspective. We pose theoretical investigations of the main limitations of TransE in the light of loss function rather than the score function. To the best of our knowledge, this has not been investigated so far comprehensively. We show that by a proper selection of the loss function for training the TransE model, the main limitations of the model are mitigated. This is explained by setting upper-bound for the scores of positive samples, showing the region of truth (i.e., the region that a triple is considered positive by the model). Our theoretical proofs with experimental results fill the gap between the capability of translation-based class of embedding models and the loss function. The theories emphasize the importance of the selection of the loss functions for training the models. Our experimental evaluations on different loss functions used for training the models justify our theoretical proofs and confirm the importance of the loss functions on the performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.00519](http://arxiv.org/abs/1909.00519)

##### PDF
[http://arxiv.org/pdf/1909.00519](http://arxiv.org/pdf/1909.00519)

