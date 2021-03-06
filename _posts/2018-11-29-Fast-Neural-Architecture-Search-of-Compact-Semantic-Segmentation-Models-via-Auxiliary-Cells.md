---
layout: post
title: "Fast Neural Architecture Search of Compact Semantic Segmentation Models via Auxiliary Cells"
date: 2018-11-29 01:41:47
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation Pose_Estimation NAS Reinforcement_Learning CNN Image_Classification Semantic_Segmentation Classification Language_Model Prediction Quantitative
author: Vladimir Nekrasov, Hao Chen, Chunhua Shen, Ian Reid
mathjax: true
---

* content
{:toc}

##### Abstract
Automated design of neural network architectures tailored for a specific task is an extremely promising, albeit inherently difficult, avenue to explore. While most results in this domain have been achieved on image classification and language modelling problems, here we concentrate on dense per-pixel tasks, in particular, semantic image segmentation using fully convolutional networks. In contrast to the aforementioned areas, the design choices of a fully convolutional network require several changes, ranging from the sort of operations that need to be used - e.g., dilated convolutions - to a solving of a more difficult optimisation problem. In this work, we are particularly interested in searching for high-performance compact segmentation architectures, able to run in real-time using limited resources. To achieve that, we intentionally over-parameterise the architecture during the training time via a set of auxiliary cells that provide an intermediate supervisory signal and can be omitted during the evaluation phase. The design of the auxiliary cell is emitted by a controller, a neural network with the fixed structure trained using reinforcement learning. More crucially, we demonstrate how to efficiently search for these architectures within limited time and computational budgets. In particular, we rely on a progressive strategy that terminates non-promising architectures from being further trained, and on Polyak averaging coupled with knowledge distillation to speed-up the convergence. Quantitatively, in 8 GPU-days our approach discovers a set of architectures performing on-par with state-of-the-art among compact models on the semantic segmentation, pose estimation and depth prediction tasks.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.10804](https://arxiv.org/abs/1810.10804)

##### PDF
[https://arxiv.org/pdf/1810.10804](https://arxiv.org/pdf/1810.10804)

