---
layout: post
title: "Estimation of Tissue Oxygen Saturation from RGB images and Sparse Hyperspectral Signals based on Conditional Generative Adversarial Network"
date: 2019-05-01 17:25:01
categories: arXiv_CV
tags: arXiv_CV Adversarial Sparse GAN Optimization Prediction Detection
author: Qingbiao Li, Jianyu Lin, Neil T.Clancy, Daniel S. Elson
mathjax: true
---

* content
{:toc}

##### Abstract
Purpose: Intra-operative measurement of tissue oxygen saturation (StO2) is important in the detection of ischemia, monitoring perfusion and identifying disease. Hyperspectral imaging (HSI) measures the optical reflectance spectrum of the tissue and uses this information to quantify its composition, including StO2. However, real-time monitoring is difficult due to the capture rate and data processing time. Methods: An endoscopic system based on a multi-fiber probe was previously developed to sparsely capture HSI data (sHSI). These were combined with RGB images, via a deep neural network, to generate high-resolution hypercubes and calculate StO2. To improve accuracy and processing speed, we propose a dual-input conditional generative adversarial network (cGAN), Dual2StO2, to directly estimate StO2 by fusing features from both RGB and sHSI. Results: Validation experiments were carried out on in vivo porcine bowel data, where the ground truth StO2 was generated from the HSI camera. The performance was also compared to our previous super-spectral-resolution network, SSRNet in terms of mean StO2 prediction accuracy and structural similarity metrics. Dual2StO2 was also tested using simulated probe data with varying fiber number. Conclusions: StO2 estimation by Dual2StO2 is visually closer to ground truth in general structure, achieves higher prediction accuracy and faster processing speed than SSRNet. Simulations showed that results improved when a greater number of fibers are used in the probe. Future work will include refinement of the network architecture, hardware optimization based on simulation results, and evaluation of the technique in clinical applications beyond StO2 estimation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.00391](http://arxiv.org/abs/1905.00391)

##### PDF
[http://arxiv.org/pdf/1905.00391](http://arxiv.org/pdf/1905.00391)

