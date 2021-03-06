---
layout: post
title: "Dual Refinement Networks for Accurate and Fast Object Detection in Real-World Scenes"
date: 2019-05-07 13:55:18
categories: arXiv_RO
tags: arXiv_RO Object_Detection Detection
author: Xingyu Chen, Junzhi Yu, Shihan Kong, Zhengxing Wu, Li Wen
mathjax: true
---

* content
{:toc}

##### Abstract
Object detection has been vigorously studied for years but fast accurate detection for real-world scenes remains a very challenging problem. Overcoming drawbacks of single-stage detectors, we take aim at precisely detecting objects for static and temporal scenes in real time. Firstly, as a dual refinement mechanism, a novel anchor-offset detection including an anchor refinement, a feature offset refinement, and a deformable detection head is designed for two-step regression and capture of accurate detection features. Based on the anchor-offset detection, a dual refinement network (DRN) is developed for high-performance static detection, where a multi-deformable head is further designed to leverage contextual information for describing objects. As for temporal detection in real-world scenes, temporal refinement networks (TRN) and temporal dual refinement networks (TDRN) are developed by propagating the refinement information across time, where we also propose a loose refinement strategy to match object motion with the previous refinement. Our proposed methods are evaluated on PASCAL VOC, COCO, and ImageNet VID datasets. Extensive comparison on static and temporal detection verify the superiority of DRN, TRN, and TDRN. Consequently, our developed approaches run in a fairly fast speed, and in the meantime achieve a significantly enhanced detection accuracy, i.e., a mAP of 82.8% on VOC 2007, 80.6% on VOC 2012, 69.4% on VID 2017, and an AP of 34.3% on COCO. Ultimately, producing encouraging results, our methods are applied to underwater object grasping with an autonomous system. Codes are publicly available at https://github.com/SeanChenxy/TDRN.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1807.08638](http://arxiv.org/abs/1807.08638)

##### PDF
[http://arxiv.org/pdf/1807.08638](http://arxiv.org/pdf/1807.08638)

