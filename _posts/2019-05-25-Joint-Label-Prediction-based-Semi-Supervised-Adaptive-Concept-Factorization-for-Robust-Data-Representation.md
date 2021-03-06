---
layout: post
title: "Joint Label Prediction based Semi-Supervised Adaptive Concept Factorization for Robust Data Representation"
date: 2019-05-25 11:18:45
categories: arXiv_CV
tags: arXiv_CV Sparse Knowledge Prediction
author: Zhao Zhang, Yan Zhang, Guangcan Liu, Jinhui Tang, Shuicheng Yan, Meng Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Constrained Concept Factorization (CCF) yields the enhanced representation ability over CF by incorporating label information as additional constraints, but it cannot classify and group unlabeled data appropriately. Minimizing the difference between the original data and its reconstruction directly can enable CCF to model a small noisy perturbation, but is not robust to gross sparse errors. Besides, CCF cannot preserve the manifold structures in new representation space explicitly, especially in an adaptive manner. In this paper, we propose a joint label prediction based Robust Semi-Supervised Adaptive Concept Factorization (RS2ACF) framework. To obtain robust representation, RS2ACF relaxes the factorization to make it simultaneously stable to small entrywise noise and robust to sparse errors. To enrich prior knowledge to enhance the discrimination, RS2ACF clearly uses class information of labeled data and more importantly propagates it to unlabeled data by jointly learning an explicit label indicator for unlabeled data. By the label indicator, RS2ACF can ensure the unlabeled data of the same predicted label to be mapped into the same class in feature space. Besides, RS2ACF incorporates the joint neighborhood reconstruction error over the new representations and predicted labels of both labeled and unlabeled data, so the manifold structures can be preserved explicitly and adaptively in the representation space and label space at the same time. Owing to the adaptive manner, the tricky process of determining the neighborhood size or kernel width can be avoided. Extensive results on public databases verify that our RS2ACF can deliver state-of-the-art data representation, compared with other related methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.10572](http://arxiv.org/abs/1905.10572)

##### PDF
[http://arxiv.org/pdf/1905.10572](http://arxiv.org/pdf/1905.10572)

