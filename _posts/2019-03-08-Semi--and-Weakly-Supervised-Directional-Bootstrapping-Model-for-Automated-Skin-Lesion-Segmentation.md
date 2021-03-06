---
layout: post
title: "Semi- and Weakly Supervised Directional Bootstrapping Model for Automated Skin Lesion Segmentation"
date: 2019-03-08 07:57:40
categories: arXiv_CV
tags: arXiv_CV Segmentation Weakly_Supervised CNN Classification Deep_Learning
author: Yutong Xie, Jianpeng Zhang, Yong Xia, Chunhua Shen
mathjax: true
---

* content
{:toc}

##### Abstract
Automated skin lesion segmentation on dermoscopy images is an essential and challenging task in the computer-aided diagnosis of skin cancer. Despite their prevalence and relatively good performance, deep learning based segmentation methods require a myriad number of training images with pixel-level dense annotation, which is hard to obtain due to the efforts and costs related to dermoscopy images acquisition and annotation. In this paper, we propose the semi- and weakly supervised directional bootstrapping (SWSDB) model for skin lesion segmentation, which consists of three deep convolutional neural networks: a coarse segmentation network (coarse-SN), a dilated classification network (dilated-CN) and an enhanced segmentation network (enhanced-SN). Both the coarse-SN and enhanced-SN are trained using the images with pixel-level annotation, and the dilated-CN is trained using the images with image-level class labels. The coarse-SN generates rough segmentation masks that provide a prior bootstrapping for the dilated-CN and help it produce accurate lesion localization maps. The maps are then fed into the enhanced-SN to transfer the localization information learned from image-level labels to the enhanced-SN to generate segmentation results. Furthermore, we introduce a hybrid loss that is the weighted sum of a dice loss and a rank loss to the coarse-SN and enhanced-SN, ensuring both networks' good compatibility for the data with imbalanced classes and imbalanced hard-easy pixels. We evaluated the proposed SWSDB model on the ISIC-2017 challenge dataset and PH2 dataset and achieved a Jaccard index of 80.4% and 89.4%, respectively, setting a new record in skin lesion segmentation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.03313](http://arxiv.org/abs/1903.03313)

##### PDF
[http://arxiv.org/pdf/1903.03313](http://arxiv.org/pdf/1903.03313)

