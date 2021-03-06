---
layout: post
title: "Edge-Direct Visual Odometry"
date: 2019-06-11 21:53:49
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Kevin Christensen, Martial Hebert
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we propose an edge-direct visual odometry algorithm that efficiently utilizes edge pixels to find the relative pose that minimizes the photometric error between images. Prior work on exploiting edge pixels instead treats edges as features and employ various techniques to match edge lines or pixels, which adds unnecessary complexity. Direct methods typically operate on all pixel intensities, which proves to be highly redundant. In contrast our method builds on direct visual odometry methods naturally with minimal added computation. It is not only more efficient than direct dense methods since we iterate with a fraction of the pixels, but also more accurate. We achieve high accuracy and efficiency by extracting edges from only one image, and utilize robust Gauss-Newton to minimize the photometric error of these edge pixels. This simultaneously finds the edge pixels in the reference image, as well as the relative camera pose that minimizes the photometric error. We test various edge detectors, including learned edges, and determine that the optimal edge detector for this method is the Canny edge detection algorithm using automatic thresholding. We highlight key differences between our edge direct method and direct dense methods, in particular how higher levels of image pyramids can lead to significant aliasing effects and result in incorrect solution convergence. We show experimentally that reducing the photometric error of edge pixels also reduces the photometric error of all pixels, and we show through an ablation study the increase in accuracy obtained by optimizing edge pixels only. We evaluate our method on the RGB-D TUM benchmark on which we achieve state-of-the-art performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.04838](http://arxiv.org/abs/1906.04838)

##### PDF
[http://arxiv.org/pdf/1906.04838](http://arxiv.org/pdf/1906.04838)

