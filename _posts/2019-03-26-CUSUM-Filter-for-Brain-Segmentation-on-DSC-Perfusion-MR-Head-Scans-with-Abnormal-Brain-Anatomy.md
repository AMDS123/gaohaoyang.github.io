---
layout: post
title: "CUSUM Filter for Brain Segmentation on DSC Perfusion MR Head Scans with Abnormal Brain Anatomy"
date: 2019-03-26 08:56:07
categories: arXiv_CV
tags: arXiv_CV Segmentation Quantitative Detection
author: Svitlana Alkhimova
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a new approach for relatively accurate brain region of interest (ROI) detection from dynamic susceptibility contrast (DSC) perfusion magnetic resonance (MR) images of a human head with abnormal brain anatomy. Such images produce problems for automatic brain segmentation algorithms, and as a result, poor perfusion ROI detection affects both quantitative measurements and visual assessment of perfusion data. In the proposed approach image segmentation is based on CUSUM filter usage that was adapted to be applicable to process DSC perfusion MR images. The result of segmentation is a binary mask of brain ROI that is generated via usage of brain boundary location. Each point of the boundary between the brain and surrounding tissues is detected as a change-point by CUSUM filter. Proposed adopted CUSUM filter operates by accumulating the deviations between the observed and expected intensities of image points at the time of moving on a trajectory. Motion trajectory is created by the iterative change of movement direction inside the background region in order to reach brain region, and vice versa after boundary crossing. Proposed segmentation approach was evaluated with Dice index comparing obtained results to the reference standard. Manually marked brain region pixels (reference standard), as well as visual inspection of detected with CUSUM filter usage brain ROI, were provided by experienced radiologists. The results showed that proposed approach is suitable to be used for brain ROI detection from DSC perfusion MR images of a human head with abnormal brain anatomy and can, therefore, be applied in the DSC perfusion data analysis.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.00787](http://arxiv.org/abs/1904.00787)

##### PDF
[http://arxiv.org/pdf/1904.00787](http://arxiv.org/pdf/1904.00787)

