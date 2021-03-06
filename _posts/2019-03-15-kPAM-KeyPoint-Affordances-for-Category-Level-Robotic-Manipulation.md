---
layout: post
title: "kPAM: KeyPoint Affordances for Category-Level Robotic Manipulation"
date: 2019-03-15 17:31:00
categories: arXiv_RO
tags: arXiv_RO Segmentation Optimization Detection
author: Lucas Manuelli, Wei Gao, Peter Florence, Russ Tedrake
mathjax: true
---

* content
{:toc}

##### Abstract
We would like robots to achieve purposeful manipulation by placing any instance from a category of objects into a desired set of goal states. Existing manipulation pipelines typically specify the desired configuration as a target 6-DOF pose and rely on explicitly estimating the pose of the manipulated objects. However, representing an object with a parameterized transformation defined on a fixed template cannot capture large intra-category shape variation, and specifying a target pose at a category level can be physically infeasible or fail to accomplish the task -- e.g. knowing the pose and size of a coffee mug relative to some canonical mug is not sufficient to successfully hang it on a rack by its handle. Hence we propose a novel formulation of category-level manipulation that uses semantic 3D keypoints as the object representation. This keypoint representation enables a simple and interpretable specification of the manipulation target as geometric costs and constraints on the keypoints, which flexibly generalizes existing pose-based manipulation methods. Using this formulation, we factor the manipulation policy into instance segmentation, 3D keypoint detection, optimization-based robot action planning and local dense-geometry-based action execution. This factorization allows us to leverage advances in these sub-problems and combine them into a general and effective perception-to-action manipulation pipeline. Our pipeline is robust to large intra-category shape variation and topology changes as the keypoint representation ignores task-irrelevant geometric details. Extensive hardware experiments demonstrate our method can reliably accomplish tasks with never-before seen objects in a category, such as placing shoes and mugs with significant shape variation into category level target configurations.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.06684](http://arxiv.org/abs/1903.06684)

##### PDF
[http://arxiv.org/pdf/1903.06684](http://arxiv.org/pdf/1903.06684)

