---
layout: post
title: "Cross-Domain Car Detection Using Unsupervised Image-to-Image Translation: From Day to Night"
date: 2019-07-19 22:37:28
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection GAN Deep_Learning Detection
author: Vinicius F. Arruda, Thiago M. Paix&#xe3;o, Rodrigo F. Berriel, Alberto F. De Souza, Claudine Badue, Nicu Sebe, Thiago Oliveira-Santos
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning techniques have enabled the emergence of state-of-the-art models to address object detection tasks. However, these techniques are data-driven, delegating the accuracy to the training dataset which must resemble the images in the target task. The acquisition of a dataset involves annotating images, an arduous and expensive process, generally requiring time and manual effort. Thus, a challenging scenario arises when the target domain of application has no annotated dataset available, making tasks in such situation to lean on a training dataset of a different domain. Sharing this issue, object detection is a vital task for autonomous vehicles where the large amount of driving scenarios yields several domains of application requiring annotated data for the training process. In this work, a method for training a car detection system with annotated data from a source domain (day images) without requiring the image annotations of the target domain (night images) is presented. For that, a model based on Generative Adversarial Networks (GANs) is explored to enable the generation of an artificial dataset with its respective annotations. The artificial dataset (fake dataset) is created translating images from day-time domain to night-time domain. The fake dataset, which comprises annotated images of only the target domain (night images), is then used to train the car detector model. Experimental results showed that the proposed method achieved significant and consistent improvements, including the increasing by more than 10% of the detection performance when compared to the training with only the available annotated data (i.e., day images).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.08719](http://arxiv.org/abs/1907.08719)

##### PDF
[http://arxiv.org/pdf/1907.08719](http://arxiv.org/pdf/1907.08719)

