---
layout: post
title: "Active Scene Learning"
date: 2019-03-07 11:07:54
categories: arXiv_CV
tags: arXiv_CV Face Recognition
author: Erelcan Yanik, Tevfik Metin Sezgin
mathjax: true
---

* content
{:toc}

##### Abstract
Sketch recognition allows natural and efficient interaction in pen-based interfaces. A key obstacle to building accurate sketch recognizers has been the difficulty of creating large amounts of annotated training data. Several authors have attempted to address this issue by creating synthetic data, and by building tools that support efficient annotation. Two prominent sets of approaches stand out from the rest of the crowd. They use interim classifiers trained with a small set of labeled data to aid the labeling of the remainder of the data. The first set of approaches uses a classifier trained with a partially labeled dataset to automatically label unlabeled instances. The others, based on active learning, save annotation effort by giving priority to labeling informative data instances. The former is sub-optimal since it doesn't prioritize the order of labeling to favor informative instances, while the latter makes the strong assumption that unlabeled data comes in an already segmented form (i.e. the ink in the training data is already assembled into groups forming isolated object instances). In this paper, we propose an active learning framework that combines the strengths of these methods, while addressing their weaknesses. In particular, we propose two methods for deciding how batches of unsegmented sketch scenes should be labeled. The first method, scene-wise selection, assesses the informativeness of each drawing (sketch scene) as a whole, and asks the user to annotate all objects in the drawing. The latter, segment-wise selection, attempts more precise targeting to locate informative fragments of drawings for user labeling. We show that both selection schemes outperform random selection. Furthermore, we demonstrate that precise targeting yields superior performance. Overall, our approach allows reaching top accuracy figures with up to 30% savings in annotation cost.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.02832](http://arxiv.org/abs/1903.02832)

##### PDF
[http://arxiv.org/pdf/1903.02832](http://arxiv.org/pdf/1903.02832)

