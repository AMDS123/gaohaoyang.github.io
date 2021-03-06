---
layout: post
title: "ROVO: Robust Omnidirectional Visual Odometry for Wide-baseline Wide-FOV Camera Systems"
date: 2019-03-01 15:45:42
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Optimization
author: Hochang Seok, Jongwoo Lim
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we propose a robust visual odometry system for a wide-baseline camera rig with wide field-of-view (FOV) fisheye lenses, which provides full omnidirectional stereo observations of the environment. For more robust and accurate ego-motion estimation we adds three components to the standard VO pipeline, 1) the hybrid projection model for improved feature matching, 2) multi-view P3P RANSAC algorithm for pose estimation, and 3) online update of rig extrinsic parameters. The hybrid projection model combines the perspective and cylindrical projection to maximize the overlap between views and minimize the image distortion that degrades feature matching performance. The multi-view P3P RANSAC algorithm extends the conventional P3P RANSAC to multi-view images so that all feature matches in all views are considered in the inlier counting for robust pose estimation. Finally the online extrinsic calibration is seamlessly integrated in the backend optimization framework so that the changes in camera poses due to shocks or vibrations can be corrected automatically. The proposed system is extensively evaluated with synthetic datasets with ground-truth and real sequences of highly dynamic environment, and its superior performance is demonstrated.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1902.11154](https://arxiv.org/abs/1902.11154)

##### PDF
[https://arxiv.org/pdf/1902.11154](https://arxiv.org/pdf/1902.11154)

