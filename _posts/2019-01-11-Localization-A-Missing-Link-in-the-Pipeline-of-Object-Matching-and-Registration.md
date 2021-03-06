---
layout: post
title: "Localization: A Missing Link in the Pipeline of Object Matching and Registration"
date: 2019-01-11 12:01:54
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation CNN Quantitative Detection
author: Deepak Mishra, Rajeev Ranjan, Santanu Chaudhury, Mukul Sarkar, Arvinder Singh Soin
mathjax: true
---

* content
{:toc}

##### Abstract
Image registration is a process of aligning two or more images of same objects using geometric transformation. Most of the existing approaches work on the assumption of location invariance. These approaches require object-centric images to perform matching. Further, in absence of intensity level symmetry between the corresponding points in two images, the learning based registration approaches rely on synthetic deformations, which often fail in real scenarios. To address these issues, a combination of convolutional neural networks (CNNs) to perform the desired registration is developed in this work. The complete objective is divided into three sub-objectives: object localization, segmentation and matching transformation. Object localization step establishes an initial correspondence between the images. A modified version of single shot multi-box detector is used for this purpose. The detected region is cropped to make the images object-centric. Subsequently, the objects are segmented and matched using a spatial transformer network employing thin plate spline deformation. Initial experiments on MNIST and Caltech-101 datasets show that the proposed model is able to produce accurate matching. Quantitative evaluation performed using dice coefficient (DC) and mean intersection over union (mIoU) show that proposed method results in the values of 79% and 66%, respectively for MNIST dataset and the values of 94% and 90%, respectively for Caltech-101 dataset. The proposed framework is extended to the registration of CT and US images, which is free from any data specific assumptions and has better generalization capability as compared to the existing rule-based/classical approaches.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.00223](http://arxiv.org/abs/1805.00223)

##### PDF
[http://arxiv.org/pdf/1805.00223](http://arxiv.org/pdf/1805.00223)

