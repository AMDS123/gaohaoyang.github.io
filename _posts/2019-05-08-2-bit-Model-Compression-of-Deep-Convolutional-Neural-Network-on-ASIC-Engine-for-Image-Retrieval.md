---
layout: post
title: "2-bit Model Compression of Deep Convolutional Neural Network on ASIC Engine for Image Retrieval"
date: 2019-05-08 21:48:42
categories: arXiv_AI
tags: arXiv_AI Image_Retrieval CNN
author: Bin Yang, Lin Yang, Xiaochun Li, Wenhan Zhang, Hua Zhou, Yequn Zhang, Yongxiong Ren, Yinbo Shi
mathjax: true
---

* content
{:toc}

##### Abstract
Image retrieval utilizes image descriptors to retrieve the most similar images to a given query image. Convolutional neural network (CNN) is becoming the dominant approach to extract image descriptors for image retrieval. For low-power hardware implementation of image retrieval, the drawback of CNN-based feature descriptor is that it requires hundreds of megabytes of storage. To address this problem, this paper applies deep model quantization and compression to CNN in ASIC chip for image retrieval. It is demonstrated that the CNN-based features descriptor can be extracted using as few as 2-bit weights quantization to deliver a similar performance as floating-point model for image retrieval. In addition, to implement CNN in ASIC, especially for large scale images, the limited buffer size of chips should be considered. To retrieve large scale images, we propose an improved pooling strategy, region nested invariance pooling (RNIP), which uses cropped sub-images for CNN. Testing results on chip show that integrating RNIP with the proposed 2-bit CNN model compression approach is capable of retrieving large scale images.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.03362](http://arxiv.org/abs/1905.03362)

##### PDF
[http://arxiv.org/pdf/1905.03362](http://arxiv.org/pdf/1905.03362)

