---
layout: post
title: "Meta-Learning via Feature-Label Memory Network"
date: 2017-10-19 12:08:59
categories: arXiv_CV
tags: arXiv_CV Inference Classification Deep_Learning Prediction
author: Dawit Mureja, Hyunsin Park, Chang D. Yoo
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning typically requires training a very capable architecture using large datasets. However, many important learning problems demand an ability to draw valid inferences from small size datasets, and such problems pose a particular challenge for deep learning. In this regard, various researches on "meta-learning" are being actively conducted. Recent work has suggested a Memory Augmented Neural Network (MANN) for meta-learning. MANN is an implementation of a Neural Turing Machine (NTM) with the ability to rapidly assimilate new data in its memory, and use this data to make accurate predictions. In models such as MANN, the input data samples and their appropriate labels from previous step are bound together in the same memory locations. This often leads to memory interference when performing a task as these models have to retrieve a feature of an input from a certain memory location and read only the label information bound to that location. In this paper, we tried to address this issue by presenting a more robust MANN. We revisited the idea of meta-learning and proposed a new memory augmented neural network by explicitly splitting the external memory into feature and label memories. The feature memory is used to store the features of input data samples and the label memory stores their labels. Hence, when predicting the label of a given input, our model uses its feature memory unit as a reference to extract the stored feature of the input, and based on that feature, it retrieves the label information of the input from the label memory unit. In order for the network to function in this framework, a new memory-writingmodule to encode label information into the label memory in accordance with the meta-learning task structure is designed. Here, we demonstrate that our model outperforms MANN by a large margin in supervised one-shot classification tasks using Omniglot and MNIST datasets.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1710.07110](https://arxiv.org/abs/1710.07110)

##### PDF
[https://arxiv.org/pdf/1710.07110](https://arxiv.org/pdf/1710.07110)

