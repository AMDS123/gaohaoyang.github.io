---
layout: post
title: "Learning 3D Human Dynamics from Video"
date: 2019-05-16 06:10:49
categories: arXiv_CV
tags: arXiv_CV Object_Detection Prediction Detection
author: Angjoo Kanazawa, Jason Y. Zhang, Panna Felsen, Jitendra Malik
mathjax: true
---

* content
{:toc}

##### Abstract
From an image of a person in action, we can easily guess the 3D motion of the person in the immediate past and future. This is because we have a mental model of 3D human dynamics that we have acquired from observing visual sequences of humans in motion. We present a framework that can similarly learn a representation of 3D dynamics of humans from video via a simple but effective temporal encoding of image features. At test time, from video, the learned temporal representation can recover smooth 3D mesh predictions. From a single image, our model can recover the current 3D mesh as well as its 3D past and future motion. Our approach is designed so it can learn from videos with 2D pose annotations in a semi-supervised manner. However, annotated data is always limited. On the other hand, there are millions of videos uploaded daily on the Internet. In this work, we harvest this Internet-scale source of unlabeled data by training our model on them with pseudo-ground truth 2D pose obtained from an off-the-shelf 2D pose detector. Our experiments show that adding more videos with pseudo-ground truth 2D pose monotonically improves 3D prediction performance. We evaluate our model, Human Mesh and Motion Recovery (HMMR), on the recent challenging dataset of 3D Poses in the Wild and obtain state-of-the-art performance on the 3D prediction task without any fine-tuning. The project website with video, code, and data can be found at https://akanazawa.github.io/human_dynamics/.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.01601](http://arxiv.org/abs/1812.01601)

##### PDF
[http://arxiv.org/pdf/1812.01601](http://arxiv.org/pdf/1812.01601)

