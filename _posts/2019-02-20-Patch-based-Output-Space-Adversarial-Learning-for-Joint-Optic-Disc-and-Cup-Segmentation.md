---
layout: post
title: "Patch-based Output Space Adversarial Learning for Joint Optic Disc and Cup Segmentation"
date: 2019-02-20 11:37:59
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation CNN
author: Shujun Wang, Lequan Yu, Xin Yang, Chi-Wing Fu, Pheng-Ann Heng
mathjax: true
---

* content
{:toc}

##### Abstract
Glaucoma is a leading cause of irreversible blindness. Accurate segmentation of the optic disc (OD) and cup (OC) from fundus images is beneficial to glaucoma screening and diagnosis. Recently, convolutional neural networks demonstrate promising progress in joint OD and OC segmentation. However, affected by the domain shift among different datasets, deep networks are severely hindered in generalizing across different scanners and institutions. In this paper, we present a novel patchbased Output Space Adversarial Learning framework (pOSAL) to jointly and robustly segment the OD and OC from different fundus image datasets. We first devise a lightweight and efficient segmentation network as a backbone. Considering the specific morphology of OD and OC, a novel morphology-aware segmentation loss is proposed to guide the network to generate accurate and smooth segmentation. Our pOSAL framework then exploits unsupervised domain adaptation to address the domain shift challenge by encouraging the segmentation in the target domain to be similar to the source ones. Since the whole-segmentationbased adversarial loss is insufficient to drive the network to capture segmentation details, we further design the pOSAL in a patch-based fashion to enable fine-grained discrimination on local segmentation details. We extensively evaluate our pOSAL framework and demonstrate its effectiveness in improving the segmentation performance on three public retinal fundus image datasets, i.e., Drishti-GS, RIM-ONE-r3, and REFUGE. Furthermore, our pOSAL framework achieved the first place in the OD and OC segmentation tasks in MICCAI 2018 Retinal Fundus Glaucoma Challenge.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.07519](http://arxiv.org/abs/1902.07519)

##### PDF
[http://arxiv.org/pdf/1902.07519](http://arxiv.org/pdf/1902.07519)

