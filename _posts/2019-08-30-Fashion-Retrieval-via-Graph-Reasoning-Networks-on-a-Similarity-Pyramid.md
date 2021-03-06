---
layout: post
title: "Fashion Retrieval via Graph Reasoning Networks on a Similarity Pyramid"
date: 2019-08-30 14:19:24
categories: arXiv_CV
tags: arXiv_CV Salient CNN
author: Zhanghui Kuang, Yiming Gao, Guanbin Li, Ping Luo, Yimin Chen, Liang Lin, Wayne Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Matching clothing images from customers and online shopping stores has rich applications in E-commerce. Existing algorithms encoded an image as a global feature vector and performed retrieval with the global representation. However, discriminative local information on clothes are submerged in this global representation, resulting in sub-optimal performance. To address this issue, we propose a novel Graph Reasoning Network (GRNet) on a Similarity Pyramid, which learns similarities between a query and a gallery cloth by using both global and local representations in multiple scales. The similarity pyramid is represented by a Graph of similarity, where nodes represent similarities between clothing components at different scales, and the final matching score is obtained by message passing along edges. In GRNet, graph reasoning is solved by training a graph convolutional network, enabling to align salient clothing components to improve clothing retrieval. To facilitate future researches, we introduce a new benchmark FindFashion, containing rich annotations of bounding boxes, views, occlusions, and cropping. Extensive experiments show that GRNet obtains new state-of-the-art results on two challenging benchmarks, e.g., pushing the top-1, top-20, and top-50 accuracies on DeepFashion to 26%, 64%, and 75% (i.e., 4%, 10%, and 10% absolute improvements), outperforming competitors with large margins. On FindFashion, GRNet achieves considerable improvements on all empirical settings.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.11754](http://arxiv.org/abs/1908.11754)

##### PDF
[http://arxiv.org/pdf/1908.11754](http://arxiv.org/pdf/1908.11754)

