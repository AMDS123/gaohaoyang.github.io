---
layout: post
title: "An Efficient Framework for Visible-Infrared Cross Modality Person Re-Identification"
date: 2019-07-15 13:32:15
categories: arXiv_CV
tags: arXiv_CV Re-identification Person_Re-identification CNN
author: Emrah Basaran, Muhittin Gokmen, Mustafa E. Kamasak
mathjax: true
---

* content
{:toc}

##### Abstract
Visible-infrared cross modality person re-identification (VI-ReId) is an important task for video surveillance in poorly illuminated or dark environments. Despite many recent studies on person re-identification in visible domain (ReId), there are few studies dealing with VI-ReId. Besides challenges that are common for both ReId and VI-ReId such as pose/illumination variations, background clutter and occlusion, VI-ReId has additional challenges as color information is not available in infrared images. As a result, the performance of VI-ReId systems is typically lower than ReId systems. In this work, we propose a 4-stream framework to improve VI-ReId performance. We train a separate deep convolutional neural network in each stream using different representations of input images. We expect that different and complementary features can be learned from each stream. In our framework, grayscale and infrared input images are used to train the ResNet in the first stream. In the second stream, RGB and 3-channel infrared images (created by repeating infrared channel) are used. In the remaining two streams, we use local pattern maps as input images. These maps are generated utilizing local Zernike moments transformation. Local pattern maps are obtained from grayscale and infrared images in the 3rd stream and from RGB and 3-channel infrared images in the last stream. We improve the performance of the proposed framework by employing a re-ranking algorithm for post processing. Our results indicate that the proposed framework outperforms current state-of-the-art on SYSU-MM01 dataset with large margin by improving Rank-1/mAP by 34.2%/37.9% and 37.4%/34.8% under all-search and indoor-search modes, respectively.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.06498](http://arxiv.org/abs/1907.06498)

##### PDF
[http://arxiv.org/pdf/1907.06498](http://arxiv.org/pdf/1907.06498)

