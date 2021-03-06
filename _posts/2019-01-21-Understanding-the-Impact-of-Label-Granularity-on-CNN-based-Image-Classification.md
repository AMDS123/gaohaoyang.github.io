---
layout: post
title: "Understanding the Impact of Label Granularity on CNN-based Image Classification"
date: 2019-01-21 17:53:43
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Optimization Classification
author: Zhuo Chen, Ruizhou Ding, Ting-Wu Chin, Diana Marculescu
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, supervised learning using Convolutional Neural Networks (CNNs) has achieved great success in image classification tasks, and large scale labeled datasets have contributed significantly to this achievement. However, the definition of a label is often application dependent. For example, an image of a cat can be labeled as "cat" or perhaps more specifically "Persian cat." We refer to this as label granularity. In this paper, we conduct extensive experiments using various datasets to demonstrate and analyze how and why training based on fine-grain labeling, such as "Persian cat" can improve CNN accuracy on classifying coarse-grain classes, in this case "cat." The experimental results show that training CNNs with fine-grain labels improves both network's optimization and generalization capabilities, as intuitively it encourages the network to learn more features, and hence increases classification accuracy on coarse-grain classes under all datasets considered. Moreover, fine-grain labels enhance data efficiency in CNN training. For example, a CNN trained with fine-grain labels and only 40% of the total training data can achieve higher accuracy than a CNN trained with the full training dataset and coarse-grain labels. These results point to two possible applications of this work: (i) with sufficient human resources, one can improve CNN performance by re-labeling the dataset with fine-grain labels, and (ii) with limited human resources, to improve CNN performance, rather than collecting more training data, one may instead use fine-grain labels for the dataset. We further propose a metric called Average Confusion Ratio to characterize the effectiveness of fine-grain labeling, and show its use through extensive experimentation. Code is available at https://github.com/cmu-enyac/Label-Granularity.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.07012](http://arxiv.org/abs/1901.07012)

##### PDF
[http://arxiv.org/pdf/1901.07012](http://arxiv.org/pdf/1901.07012)

