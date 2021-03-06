---
layout: post
title: "A Functional Representation for Graph Matching"
date: 2019-01-16 08:46:21
categories: arXiv_CV
tags: arXiv_CV QA Optimization Recognition
author: Fu-Dong Wang, Gui-Song Xia, Nan Xue, Yipeng Zhang, Marcello Pelillo
mathjax: true
---

* content
{:toc}

##### Abstract
Graph matching is an important and persistent problem in computer vision and pattern recognition for finding node-to-node correspondence between graph-structured data. However, as widely used, graph matching that incorporates pairwise constraints can be formulated as a quadratic assignment problem (QAP), which is NP-complete and results in intrinsic computational difficulties. In this paper, we present a functional representation for graph matching (FRGM) that aims to provide more geometric insights on the problem and reduce the space and time complexities of corresponding algorithms. To achieve these goals, we represent a graph endowed with edge attributes by a linear function space equipped with a functional such as inner product or metric, that has an explicit geometric meaning. Consequently, the correspondence between graphs can be represented as a linear representation map of that functional. Specifically, we reformulate the linear functional representation map as a new parameterization for Euclidean graph matching, which is associative with geometric parameters for graphs under rigid or nonrigid deformations. This allows us to estimate the correspondence and geometric deformations simultaneously. The use of the representation of edge attributes rather than the affinity matrix enables us to reduce the space complexity by two orders of magnitudes. Furthermore, we propose an efficient optimization strategy with low time complexity to optimize the objective function. The experimental results on both synthetic and real-world datasets demonstrate that the proposed FRGM can achieve state-of-the-art performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.05179](http://arxiv.org/abs/1901.05179)

##### PDF
[http://arxiv.org/pdf/1901.05179](http://arxiv.org/pdf/1901.05179)

