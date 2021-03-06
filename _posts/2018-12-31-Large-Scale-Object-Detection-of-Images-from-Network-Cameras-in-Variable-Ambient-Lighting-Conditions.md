---
layout: post
title: "Large-Scale Object Detection of Images from Network Cameras in Variable Ambient Lighting Conditions"
date: 2018-12-31 17:06:44
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Caleb Tung, Matthew R. Kelleher, Ryan J. Schlueter, Binhan Xu, Yung-Hsiang Lu, George K. Thiruvathukal, Yen-Kuang Chen, Yang Lu
mathjax: true
---

* content
{:toc}

##### Abstract
Computer vision relies on labeled datasets for training and evaluation in detecting and recognizing objects. The popular computer vision program, YOLO ("You Only Look Once"), has been shown to accurately detect objects in many major image datasets. However, the images found in those datasets, are independent of one another and cannot be used to test YOLO's consistency at detecting the same object as its environment (e.g. ambient lighting) changes. This paper describes a novel effort to evaluate YOLO's consistency for large-scale applications. It does so by working (a) at large scale and (b) by using consecutive images from a curated network of public video cameras deployed in a variety of real-world situations, including traffic intersections, national parks, shopping malls, university campuses, etc. We specifically examine YOLO's ability to detect objects in different scenarios (e.g., daytime vs. night), leveraging the cameras' ability to rapidly retrieve many successive images for evaluating detection consistency. Using our camera network and advanced computing resources (supercomputers), we analyzed more than 5 million images captured by 140 network cameras in 24 hours. Compared with labels marked by humans (considered as "ground truth"), YOLO struggles to consistently detect the same humans and cars as their positions change from one frame to the next; it also struggles to detect objects at night time. Our findings suggest that state-of-the art vision solutions should be trained by data from network camera with contextual information before they can be deployed in applications that demand high consistency on object detection.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1812.11901](https://arxiv.org/abs/1812.11901)

##### PDF
[https://arxiv.org/pdf/1812.11901](https://arxiv.org/pdf/1812.11901)

