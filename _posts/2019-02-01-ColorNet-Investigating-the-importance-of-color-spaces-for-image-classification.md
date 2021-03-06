---
layout: post
title: "ColorNet: Investigating the importance of color spaces for image classification"
date: 2019-02-01 10:35:18
categories: arXiv_CV
tags: arXiv_CV Image_Classification Classification
author: Shreyank N Gowda, Chun Yuan
mathjax: true
---

* content
{:toc}

##### Abstract
Image classification is a fundamental application in computer vision. Recently, deeper networks and highly connected networks have shown state of the art performance for image classification tasks. Most datasets these days consist of a finite number of color images. These color images are taken as input in the form of RGB images and classification is done without modifying them. We explore the importance of color spaces and show that color spaces (essentially transformations of original RGB images) can significantly affect classification accuracy. Further, we show that certain classes of images are better represented in particular color spaces and for a dataset with a highly varying number of classes such as CIFAR and Imagenet, using a model that considers multiple color spaces within the same model gives excellent levels of accuracy. Also, we show that such a model, where the input is preprocessed into multiple color spaces simultaneously, needs far fewer parameters to obtain high accuracy for classification. For example, our model with 1.75M parameters significantly outperforms DenseNet 100-12 that has 12M parameters and gives results comparable to Densenet-BC-190-40 that has 25.6M parameters for classification of four competitive image classification datasets namely: CIFAR-10, CIFAR-100, SVHN and Imagenet. Our model essentially takes an RGB image as input, simultaneously converts the image into 7 different color spaces and uses these as inputs to individual densenets. We use small and wide densenets to reduce computation overhead and number of hyperparameters required. We obtain significant improvement on current state of the art results on these datasets as well.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.00267](http://arxiv.org/abs/1902.00267)

##### PDF
[http://arxiv.org/pdf/1902.00267](http://arxiv.org/pdf/1902.00267)

