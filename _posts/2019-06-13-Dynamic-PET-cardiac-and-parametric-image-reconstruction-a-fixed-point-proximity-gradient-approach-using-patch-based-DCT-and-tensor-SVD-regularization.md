---
layout: post
title: "Dynamic PET cardiac and parametric image reconstruction: a fixed-point proximity gradient approach using patch-based DCT and tensor SVD regularization"
date: 2019-06-13 19:06:11
categories: arXiv_CV
tags: arXiv_CV Regularization Sparse Quantitative
author: Ida Häggström, Yizun Lin, Si Li, Andrzej Krol, Yuesheng Xu, C. Ross Schmidtlein
mathjax: true
---

* content
{:toc}

##### Abstract
Our aim was to enhance visual quality and quantitative accuracy of dynamic positron emission tomography (PET)uptake images by improved image reconstruction, using sophisticated sparse penalty models that incorporate both 2D spatial+1D temporal (3DT) information. We developed two new 3DT PET reconstruction algorithms, incorporating different temporal and spatial penalties based on discrete cosine transform (DCT)w/ patches, and tensor nuclear norm (TNN) w/ patches, and compared to frame-by-frame methods; conventional 2D ordered subsets expectation maximization (OSEM) w/ post-filtering and 2D-DCT and 2D-TNN. A 3DT brain phantom with kinetic uptake (2-tissue model), and a moving 3DT cardiac/lung phantom was simulated and reconstructed. For the cardiac/lung phantom, an additional cardiac gated 2D-OSEM set was reconstructed. The structural similarity index (SSIM) and relative root mean squared error (rRMSE) relative ground truth was investigated. The image derived left ventricular (LV) volume for the cardiac/lung images was found by region growing and parametric images of the brain phantom were calculated. For the cardiac/lung phantom, 3DT-TNN yielded optimal images, and 3DT-DCT was best for the brain phantom. The optimal LV volume from the 3DT-TNN images was on average 11 and 55 percentage points closer to the true value compared to cardiac gated 2D-OSEM and 2D-OSEM respectively. Compared to 2D-OSEM, parametric images based on 3DT-DCT images generally had smaller bias and higher SSIM. Our novel methods that incorporate both 2D spatial and 1D temporal penalties produced dynamic PET images of higher quality than conventional 2D methods, w/o need for post-filtering. Breathing and cardiac motion were simultaneously captured w/o need for respiratory or cardiac gating. LV volumes were better recovered, and subsequently fitted parametric images were generally less biased and of higher quality.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1906.05897](https://arxiv.org/abs/1906.05897)

##### PDF
[https://arxiv.org/pdf/1906.05897](https://arxiv.org/pdf/1906.05897)

