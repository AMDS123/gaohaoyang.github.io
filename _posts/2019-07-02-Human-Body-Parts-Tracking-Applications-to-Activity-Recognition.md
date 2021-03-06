---
layout: post
title: "Human Body Parts Tracking: Applications to Activity Recognition"
date: 2019-07-02 12:40:13
categories: arXiv_CV
tags: arXiv_CV Attention Tracking Recognition
author: Aras R. Dargazany
mathjax: true
---

* content
{:toc}

##### Abstract
As cameras and computers became popular, the applications of computer vision techniques attracted attention enormously. One of the most important applications in the computer vision community is human activity recognition. In order to recognize human activities, we propose a human body parts tracking system that tracks human body parts such as head, torso, arms and legs in order to perform activity recognition tasks in real time. This thesis presents a real-time human body parts tracking system (i.e. HBPT) from video sequences. Our body parts model is mostly represented by body components such as legs, head, torso and arms. The body components are modeled using torso location and size which are obtained by a torso tracking method in each frame. In order to track the torso, we are using a blob tracking module to find the approximate location and size of the torso in each frame. By tracking the torso, we will be able to track other body parts based on their location with respect to the torso on the detected silhouette. In the proposed method for human body part tracking, we are also using a refining module to improve the detected silhouette by refining the foreground mask (i.e. obtained by background subtraction) in order to detect the body parts with respect to torso location and size. Having found the torso size and location, the region of each human body part on the silhouette will be modeled by a 2D-Gaussian blob in each frame in order to show its location, size and pose. The proposed approach described in this thesis tracks accurately the body parts in different illumination conditions and in the presence of partial occlusions. The proposed approach is applied to activity recognition tasks such as approaching an object, carrying an object and opening a box or suitcase.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.05281](http://arxiv.org/abs/1907.05281)

##### PDF
[http://arxiv.org/pdf/1907.05281](http://arxiv.org/pdf/1907.05281)

