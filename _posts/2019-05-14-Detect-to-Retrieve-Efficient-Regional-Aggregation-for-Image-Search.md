---
layout: post
title: "Detect-to-Retrieve: Efficient Regional Aggregation for Image Search"
date: 2019-05-14 00:47:47
categories: arXiv_CV
tags: arXiv_CV Image_Caption Image_Retrieval Object_Detection Detection
author: Marvin Teichmann, Andre Araujo, Menglong Zhu, Jack Sim
mathjax: true
---

* content
{:toc}

##### Abstract
Retrieving object instances among cluttered scenes efficiently requires compact yet comprehensive regional image representations. Intuitively, object semantics can help build the index that focuses on the most relevant regions. However, due to the lack of bounding-box datasets for objects of interest among retrieval benchmarks, most recent work on regional representations has focused on either uniform or class-agnostic region selection. In this paper, we first fill the void by providing a new dataset of landmark bounding boxes, based on the Google Landmarks dataset, that includes $86k$ images with manually curated boxes from $15k$ unique landmarks. Then, we demonstrate how a trained landmark detector, using our new dataset, can be leveraged to index image regions and improve retrieval accuracy while being much more efficient than existing regional methods. In addition, we introduce a novel regional aggregated selective match kernel (R-ASMK) to effectively combine information from detected regions into an improved holistic image representation. R-ASMK boosts image retrieval accuracy substantially with no dimensionality increase, while even outperforming systems that index image regions independently. Our complete image retrieval system improves upon the previous state-of-the-art by significant margins on the Revisited Oxford and Paris datasets. Code and data available at the project webpage: https://github.com/tensorflow/models/tree/master/research/delf.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.01584](http://arxiv.org/abs/1812.01584)

##### PDF
[http://arxiv.org/pdf/1812.01584](http://arxiv.org/pdf/1812.01584)

