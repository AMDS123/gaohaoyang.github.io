---
layout: post
title: "3D Object Recognition with Ensemble Learning --- A Study of Point Cloud-Based Deep Learning Models"
date: 2019-04-17 09:51:12
categories: arXiv_AI
tags: arXiv_AI Object_Detection Inference Classification Deep_Learning Detection Recognition
author: Daniel Koguciuk, &#x141;ukasz Chechli&#x144;ski
mathjax: true
---

* content
{:toc}

##### Abstract
In this study, we present an analysis of model-based ensemble learning for 3D point-cloud object classification and detection. An ensemble of multiple model instances is known to outperform a single model instance, but there is little study of the topic of ensemble learning for 3D point clouds. First, an ensemble of multiple model instances trained on the same part of the $\textit{ModelNet40}$ dataset was tested for seven deep learning, point cloud-based classification algorithms: $\textit{PointNet}$, $\textit{PointNet++}$, $\textit{SO-Net}$, $\textit{KCNet}$, $\textit{DeepSets}$, $\textit{DGCNN}$, and $\textit{PointCNN}$. Second, the ensemble of different architectures was tested. Results of our experiments show that the tested ensemble learning methods improve over state-of-the-art on the $\textit{ModelNet40}$ dataset, from $92.65\%$ to $93.64\%$ for the ensemble of single architecture instances, $94.03\%$ for two different architectures, and $94.15\%$ for five different architectures. We show that the ensemble of two models with different architectures can be as effective as the ensemble of 10 models with the same architecture. Third, a study on classic bagging i.e. with different subsets used for training multiple model instances) was tested and sources of ensemble accuracy growth were investigated for best-performing architecture, i.e. $\textit{SO-Net}$. We also investigate the ensemble learning of $\textit{Frustum PointNet}$ approach in the task of 3D object detection, increasing the average precision of 3D box detection on the $\textit{KITTI}$ dataset from $63.1\%$ to $66.5\%$ using only three model instances. We measure the inference time of all 3D classification architectures on a $\textit{Nvidia Jetson TX2}$, a common embedded computer for mobile robots, to allude to the use of these models in real-life applications.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08159](http://arxiv.org/abs/1904.08159)

##### PDF
[http://arxiv.org/pdf/1904.08159](http://arxiv.org/pdf/1904.08159)

