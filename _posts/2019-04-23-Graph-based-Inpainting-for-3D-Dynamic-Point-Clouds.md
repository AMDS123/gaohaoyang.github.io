---
layout: post
title: "Graph-based Inpainting for 3D Dynamic Point Clouds"
date: 2019-04-23 08:18:56
categories: arXiv_CV
tags: arXiv_CV Attention Optimization
author: Zeqing Fu, Wei Hu, Zongming Guo
mathjax: true
---

* content
{:toc}

##### Abstract
With the development of depth sensors and 3D laser scanning techniques, 3D dynamic point clouds have attracted increasing attention as a format for the representation of 3D objects in motion, with applications in various fields such as 3D immersive tele-presence, navigation, animation, gaming and virtual reality. However, dynamic point clouds usually exhibit holes of missing data, mainly due to the fast motion, the limitation of acquisition techniques and complicated structure. Further, point clouds are defined on irregular non-Euclidean domain, which is challenging to address with conventional methods for regular data. Hence, leveraging on graph signal processing tools, we propose an efficient dynamic point cloud inpainting method, exploiting both the inter-frame coherence and the intra-frame self-similarity in 3D dynamic point clouds. Specifically, for each frame in a point cloud sequence, we first split it into cubes of fixed size as the processing unit, and treat cubes with holes inside as target cubes. Secondly, we take advantage of the intra-frame self-similarity in the target frame, by globally searching for the most similar cube to each target cube as the intra-source cube. Thirdly, we exploit the inter-frame coherence among every three consecutive frames, by searching the corresponding cubes in the previous and subsequent frames for each target cube as the inter-source cubes, which contains most nearest neighbors of the target cube in the relative location. Finally, we formulate dynamic point cloud inpainting as an optimization problem based on both intra- and inter-source cubes, which is regularized by the graph-signal smoothness prior. Experimental results show that the proposed approach outperforms three competing methods significantly, both in objective and subjective quality.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.10795](http://arxiv.org/abs/1904.10795)

##### PDF
[http://arxiv.org/pdf/1904.10795](http://arxiv.org/pdf/1904.10795)

