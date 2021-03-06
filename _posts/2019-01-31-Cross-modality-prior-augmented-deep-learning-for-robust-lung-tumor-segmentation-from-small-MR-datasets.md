---
layout: post
title: "Cross-modality prior augmented deep learning for robust lung tumor segmentation from small MR datasets"
date: 2019-01-31 14:17:36
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation Deep_Learning
author: Jue Jiang, Yu-Chi Hu, Neelam Tyagi, Pengpeng Zhang, Andreas Rimner, Joseph O. Deasy, Harini Veeraraghavan
mathjax: true
---

* content
{:toc}

##### Abstract
Lack of large expert annotated MR datasets makes training deep learning models difficult. Therefore, a cross-modality (MR-CT) deep learning segmentation approach that augments training data using pseudo MR images produced by transforming expert-segmented CT images was developed. Eighty-One T2-weighted MRI scans from 28 patients with non-small cell lung cancers were analyzed. Cross-modality prior encoding the transformation of CT to pseudo MR images resembling T2w MRI was learned as a generative adversarial deep learning model. This model augmented training data arising from 6 expert-segmented T2w MR patient scans with 377 pseudo MRI from non-small cell lung cancer CT patient scans with obtained from the Cancer Imaging Archive. A two-dimensional Unet implemented with batch normalization was trained to segment the tumors from T2w MRI. This method was benchmarked against (a) standard data augmentation and two state-of-the art cross-modality pseudo MR-based augmentation and (b) two segmentation networks. Segmentation accuracy was computed using Dice similarity coefficient (DSC), Hausdroff distance metrics, and volume ratio. The proposed approach produced the lowest statistical variability in the intensity distribution between pseudo and T2w MR images measured as Kullback-Leibler divergence of 0.069. This method produced the highest segmentation accuracy with a DSC of 0.75 and the lowest Hausdroff distance on the test dataset. This approach produced highly similar estimations of tumor growth as an expert (P = 0.37). A novel deep learning MR segmentation was developed that overcomes the limitation of learning robust models from small datasets by leveraging learned cross-modality priors to augment training. The results show the feasibility of the approach and the corresponding improvement over the state-of-the-art methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.11369](http://arxiv.org/abs/1901.11369)

##### PDF
[http://arxiv.org/pdf/1901.11369](http://arxiv.org/pdf/1901.11369)

