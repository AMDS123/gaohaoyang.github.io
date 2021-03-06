---
layout: post
title: "Biometric Fish Classification of Temperate Species Using Convolutional Neural Network with Squeeze-and-Excitation"
date: 2019-04-04 19:50:49
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN Transfer_Learning Classification Recognition
author: Erlend Olsvik, Christian M. D. Trinh, Kristian Muri Knausgård, Arne Wiklund, Tonje Knutsen Sørdalen, Alf Ring Kleiven, Lei Jiao, Morten Goodwin
mathjax: true
---

* content
{:toc}

##### Abstract
Our understanding and ability to effectively monitor and manage coastal ecosystems are severely limited by observation methods. Automatic recognition of species in natural environment is a promising tool which would revolutionize video and image analysis for a wide range of applications in marine ecology. However, classifying fish from images captured by underwater cameras is in general very challenging due to noise and illumination variations in water. Previous classification methods in the literature relies on filtering the images to separate the fish from the background or sharpening the images by removing background noise. This pre-filtering process may negatively impact the classification accuracy. In this work, we propose a Convolutional Neural Network (CNN) using the Squeeze-and-Excitation (SE) architecture for classifying images of fish without pre-filtering. Different from conventional schemes, this scheme is divided into two steps. The first step is to train the fish classifier via a public data set, i.e., Fish4Knowledge, without using image augmentation, named as pre-training. The second step is to train the classifier based on a new data set consisting of species that we are interested in for classification, named as post-training. The weights obtained from pre-training are applied to post-training as a priori. This is also known as transfer learning. Our solution achieves the state-of-the-art accuracy of 99.27% accuracy on the pre-training. The accuracy on the post-training is 83.68%. Experiments on the post-training with image augmentation yields an accuracy of 87.74%, indicating that the solution is viable with a larger data set.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1904.02768](https://arxiv.org/abs/1904.02768)

##### PDF
[https://arxiv.org/pdf/1904.02768](https://arxiv.org/pdf/1904.02768)

