---
layout: post
title: "A High-Efficiency Framework for Constructing Large-Scale Face Parsing Benchmark"
date: 2019-05-13 02:17:56
categories: arXiv_CV
tags: arXiv_CV Knowledge Face Detection Face_Detection Recognition Face_Recognition
author: Yinglu Liu, Hailin Shi, Yue Si, Hao Shen, Xiaobo Wang, Tao Mei
mathjax: true
---

* content
{:toc}

##### Abstract
Face parsing, which is to assign a semantic label to each pixel in face images, has recently attracted increasing interest due to its huge application potentials. Although many face related fields (e.g., face recognition and face detection) have been well studied for many years, the existing datasets for face parsing are still severely limited in terms of the scale and quality, e.g., the widely used Helen dataset only contains 2,330 images. This is mainly because pixel-level annotation is a high cost and time-consuming work, especially for the facial parts without clear boundaries. The lack of accurate annotated datasets becomes a major obstacle in the progress of face parsing task. It is a feasible way to utilize dense facial landmarks to guide the parsing annotation. However, annotating dense landmarks on human face encounters the same issues as the parsing annotation. To overcome the above problems, in this paper, we develop a high-efficiency framework for face parsing annotation, which considerably simplifies and speeds up the parsing annotation by two consecutive modules. Benefit from the proposed framework, we construct a new Dense Landmark Guided Face Parsing (LaPa) benchmark. It consists of 22,000 face images with large variations in expression, pose, occlusion, etc. Each image is provided with accurate annotation of a 11-category pixel-level label map along with coordinates of 106-point landmarks. To the best of our knowledge, it is currently the largest public dataset for face parsing. To make full use of our LaPa dataset with abundant face shape and boundary priors, we propose a simple yet effective Boundary-Sensitive Parsing Network (BSPNet). Our network is taken as a baseline model on the proposed LaPa dataset, and meanwhile, it achieves the state-of-the-art performance on the Helen dataset without resorting to extra face alignment.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.04830](http://arxiv.org/abs/1905.04830)

##### PDF
[http://arxiv.org/pdf/1905.04830](http://arxiv.org/pdf/1905.04830)

