---
layout: post
title: "A Novel Loss Function Incorporating Imaging Acquisition Physics for PET Attenuation Map Generation using Deep Learning"
date: 2019-09-03 18:40:52
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning Quantitative
author: Luyao Shi, John A. Onofrey, Enette Mae Revilla, Takuya Toyonaga, David Menard, Jo-seph Ankrah, Richard E. Carson, Chi Liu, Yihuan Lu
mathjax: true
---

* content
{:toc}

##### Abstract
In PET/CT imaging, CT is used for PET attenuation correction (AC). Mismatch between CT and PET due to patient body motion results in AC artifacts. In addition, artifact caused by metal, beam-hardening and count-starving in CT itself also introduces inaccurate AC for PET. Maximum likelihood reconstruction of activity and attenuation (MLAA) was proposed to solve those issues by simultaneously reconstructing tracer activity ($\lambda$-MLAA) and attenuation map ($\mu$-MLAA) based on the PET raw data only. However, $\mu$-MLAA suffers from high noise and $\lambda$-MLAA suffers from large bias as compared to the reconstruction using the CT-based attenuation map ($\mu$-CT). Recently, a convolutional neural network (CNN) was applied to predict the CT attenuation map ($\mu$-CNN) from $\lambda$-MLAA and $\mu$-MLAA, in which an image-domain loss (IM-loss) function between the $\mu$-CNN and the ground truth $\mu$-CT was used. However, IM-loss does not directly measure the AC errors according to the PET attenuation physics, where the line-integral projection of the attenuation map ($\mu$) along the path of the two annihilation events, instead of the $\mu$ itself, is used for AC. Therefore, a network trained with the IM-loss may yield suboptimal performance in the $\mu$ generation. Here, we propose a novel line-integral projection loss (LIP-loss) function that incorporates the PET attenuation physics for $\mu$ generation. Eighty training and twenty testing datasets of whole-body 18F-FDG PET and paired ground truth $\mu$-CT were used. Quantitative evaluations showed that the model trained with the additional LIP-loss was able to significantly outperform the model trained solely based on the IM-loss function.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.01394](http://arxiv.org/abs/1909.01394)

##### PDF
[http://arxiv.org/pdf/1909.01394](http://arxiv.org/pdf/1909.01394)

