---
layout: post
title: "Texture Synthesis Guided Deep Hashing for Texture Image Retrieval"
date: 2019-04-20 17:43:57
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Attention Deep_Learning
author: Ayan Kumar Bhunia, Perla Sai Raj Kishore, Pranay Mukherjee, Abhirup Das, Partha Pratim Roy
mathjax: true
---

* content
{:toc}

##### Abstract
With the large-scale explosion of images and videos over the internet, efficient hashing methods have been developed to facilitate memory and time efficient retrieval of similar images. However, none of the existing works uses hashing to address texture image retrieval mostly because of the lack of sufficiently large texture image databases. Our work addresses this problem by developing a novel deep learning architecture that generates binary hash codes for input texture images. For this, we first pre-train a Texture Synthesis Network (TSN) which takes a texture patch as input and outputs an enlarged view of the texture by injecting newer texture content. Thus it signifies that the TSN encodes the learnt texture specific information in its intermediate layers. In the next stage, a second network gathers the multi-scale feature representations from the TSN's intermediate layers using channel-wise attention, combines them in a progressive manner to a dense continuous representation which is finally converted into a binary hash code with the help of individual and pairwise label information. The new enlarged texture patches also help in data augmentation to alleviate the problem of insufficient texture data and are used to train the second stage of the network. Experiments on three public texture image retrieval datasets indicate the superiority of our texture synthesis guided hashing approach over current state-of-the-art methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.01401](http://arxiv.org/abs/1811.01401)

##### PDF
[http://arxiv.org/pdf/1811.01401](http://arxiv.org/pdf/1811.01401)

