---
layout: post
title: "End-to-end Lane Detection through Differentiable Least-Squares Fitting"
date: 2019-02-01 12:05:47
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation GAN Detection
author: Bert De Brabandere, Wouter Van Gansbeke, Davy Neven, Marc Proesmans, Luc Van Gool
mathjax: true
---

* content
{:toc}

##### Abstract
Lane detection is typically tackled with a two-step pipeline in which a segmentation mask of the lane markings is predicted first, and a lane line model (like a parabola or spline) is fitted to the post-processed mask next. The problem with such a two-step approach is that the parameters of the network are not optimized for the true task of interest (estimating the lane curvature parameters) but for a proxy task (segmenting the lane markings), resulting in sub-optimal performance. In this work, we propose a method to train a lane detector in an end-to-end manner, directly regressing the lane parameters. The architecture consists of two components: a deep network that predicts a segmentation-like weight map for each lane line, and a differentiable least-squares fitting module that returns for each map the parameters of the best-fitting curve in the weighted least-squares sense. These parameters can subsequently be supervised with a loss function of choice. Our method relies on the observation that it is possible to backpropagate through a least-squares fitting procedure. This leads to an end-to-end method where the features are optimized for the true task of interest: the network implicitly learns to generate features that prevent instabilities during the model fitting step, as opposed to two-step pipelines that need to handle outliers with heuristics. Additionally, the system is not just a black box but offers a degree of interpretability because the intermediately generated segmentation-like weight maps can be inspected and visualized. Code and a video is available at github.com/wvangansbeke/LaneDetection_End2End.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.00293](http://arxiv.org/abs/1902.00293)

##### PDF
[http://arxiv.org/pdf/1902.00293](http://arxiv.org/pdf/1902.00293)

