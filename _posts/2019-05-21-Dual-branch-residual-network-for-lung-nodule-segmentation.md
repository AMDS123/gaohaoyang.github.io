---
layout: post
title: "Dual-branch residual network for lung nodule segmentation"
date: 2019-05-21 02:57:56
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Haichao Cao, Hong Liu, Enmin Song, Chih-Cheng Hung, Guangzhi Ma, Xiangyang Xu, Renchao Jin, Jianguo Lu
mathjax: true
---

* content
{:toc}

##### Abstract
An accurate segmentation of lung nodules in computed tomography (CT) images is critical to lung cancer analysis and diagnosis. However, due to the variety of lung nodules and the similarity of visual characteristics between nodules and their surroundings, a robust segmentation of nodules becomes a challenging problem. In this study, we propose the Dual-branch Residual Network (DB-ResNet) which is a data-driven model. Our approach integrates two new schemes to improve the generalization capability of the model: 1) the proposed model can simultaneously capture multi-view and multi-scale features of different nodules in CT images; 2) we combine the features of the intensity and the convolution neural networks (CNN). We propose a pooling method, called the central intensity-pooling layer (CIP), to extract the intensity features of the center voxel of the block, and then use the CNN to obtain the convolutional features of the center voxel of the block. In addition, we designed a weighted sampling strategy based on the boundary of nodules for the selection of those voxels using the weighting score, to increase the accuracy of the model. The proposed method has been extensively evaluated on the LIDC dataset containing 986 nodules. Experimental results show that the DB-ResNet achieves superior segmentation performance with an average dice score of 82.74% on the dataset. Moreover, we compared our results with those of four radiologists on the same dataset. The comparison showed that our average dice score was 0.49% higher than that of human experts. This proves that our proposed method is as good as the experienced radiologist.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.08413](http://arxiv.org/abs/1905.08413)

##### PDF
[http://arxiv.org/pdf/1905.08413](http://arxiv.org/pdf/1905.08413)

