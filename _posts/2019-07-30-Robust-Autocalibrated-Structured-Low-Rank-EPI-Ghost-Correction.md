---
layout: post
title: "Robust Autocalibrated Structured Low-Rank EPI Ghost Correction"
date: 2019-07-30 23:40:15
categories: arXiv_CV
tags: arXiv_CV
author: Rodrigo A. Lobos, W. Scott Hoge, Ahsan Javed, Congyu Liao, Kawin Setsompop, Krishna S. Nayak, Justin P. Haldar
mathjax: true
---

* content
{:toc}

##### Abstract
Purpose: We propose and evaluate a new structured low-rank method for EPI ghost correction called Robust Autocalibrated LORAKS (RAC-LORAKS). The method can be used to suppress EPI ghosts arising from the differences between different readout gradient polarities and/or the differences between different shots. It does not require conventional EPI navigator signals, and is robust to imperfect autocalibration data. 
 Methods: Autocalibrated LORAKS is a previous structured low-rank method for EPI ghost correction that uses GRAPPA-type autocalibration data to enable high-quality ghost correction. This method works well when the autocalibration data is pristine, but performance degrades substantially when the autocalibration information is imperfect. RAC-LORAKS generalizes Autocalibrated LORAKS in two ways. First, it does not completely trust the information from autocalibration data, and instead considers the autocalibration and EPI data simultaneously when estimating low-rank matrix structure. And second, it uses complementary information from the autocalibration data to improve EPI reconstruction in a multi-contrast joint reconstruction framework. RAC-LORAKS is evaluated using simulations and in vivo data, and compared to state-of-the-art methods. 
 Results: RAC-LORAKS is demonstrated to have good ghost elimination performance compared to state-of-the-art methods in several complicated acquisition scenarios (including gradient-echo brain imaging, diffusion-encoded brain imaging, and cardiac imaging). 
 Conclusion: RAC-LORAKS provides effective suppression of EPI ghosts and is robust to imperfect autocalibration data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.13261](http://arxiv.org/abs/1907.13261)

##### PDF
[http://arxiv.org/pdf/1907.13261](http://arxiv.org/pdf/1907.13261)

