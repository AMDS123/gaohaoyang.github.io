---
layout: post
title: "Product Image Recognition with Guidance Learning and Noisy Supervision"
date: 2019-07-26 05:13:13
categories: arXiv_CV
tags: arXiv_CV Review Knowledge CNN Recognition
author: Qing Li, Xiaojiang Peng, Liangliang Cao, Wenbin Du, Hao Xing, Yu Qiao
mathjax: true
---

* content
{:toc}

##### Abstract
This paper considers recognizing products from daily photos, which is an important problem in real-world applications but also challenging due to background clutters, category diversities, noisy labels, etc. We address this problem by two contributions. First, we introduce a novel large-scale product image dataset, termed as Product-90. Instead of collecting product images by labor-and time-intensive image capturing, we take advantage of the web and download images from the reviews of several e-commerce websites where the images are casually captured by consumers. Labels are assigned automatically by the categories of e-commerce websites. Totally the Product-90 consists of more than 140K images with 90 categories. Due to the fact that consumers may upload unrelated images, it is inevitable that our Product-90 introduces noisy labels. As the second contribution, we develop a simple yet efficient \textit{guidance learning} (GL) method for training convolutional neural networks (CNNs) with noisy supervision. The GL method first trains an initial teacher network with the full noisy dataset, and then trains a target/student network with both large-scale noisy set and small manually-verified clean set in a multi-task manner. Specifically, in the stage of student network training, the large-scale noisy data is supervised by its guidance knowledge which is the combination of its given noisy label and the soften label from the teacher network. We conduct extensive experiments on our Products-90 and public datasets, namely Food101, Food-101N, and Clothing1M. Our guidance learning method achieves performance superior to state-of-the-art methods on these datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.11384](http://arxiv.org/abs/1907.11384)

##### PDF
[http://arxiv.org/pdf/1907.11384](http://arxiv.org/pdf/1907.11384)

