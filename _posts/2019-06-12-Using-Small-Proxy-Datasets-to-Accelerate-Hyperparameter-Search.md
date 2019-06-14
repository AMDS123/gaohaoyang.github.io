---
layout: post
title: "Using Small Proxy Datasets to Accelerate Hyperparameter Search"
date: 2019-06-12 02:01:30
categories: arXiv_CV
tags: arXiv_CV
author: Sam Shleifer, Eric Prokop
mathjax: true
---

* content
{:toc}

##### Abstract
One of the biggest bottlenecks in a machine learning workflow is waiting for models to train. Depending on the available computing resources, it can take days to weeks to train a neural network on a large dataset with many classes such as ImageNet. For researchers experimenting with new algorithmic approaches, this is impractically time consuming and costly. We aim to generate smaller "proxy datasets" where experiments are cheaper to run but results are highly correlated with experimental results on the full dataset. We generate these proxy datasets using by randomly sampling from examples or classes, training on only the easiest or hardest examples and training on synthetic examples generated by "data distillation". We compare these techniques to the more widely used baseline of training on the full dataset for fewer epochs. For each proxying strategy, we estimate three measures of "proxy quality": how much of the variance in experimental results on the full dataset can be explained by experimental results on the proxy dataset. 
 Experiments on Imagenette and Imagewoof (Howard, 2019) show that running hyperparameter search on the easiest 10% of examples explains 81% of the variance in experiment results on the target task, and using the easiest 50% of examples can explain 95% of the variance, significantly more than training on all the data for fewer epochs, a more widely used baseline. These "easy" proxies are higher quality than training on the full dataset for a reduced number of epochs (but equivalent computational cost), and, unexpectedly, higher quality than proxies constructed from the hardest examples. Without access to a trained model, researchers can improve proxy quality by restricting the subset to fewer classes; proxies built on half the classes are higher quality than those with an equivalent number of examples spread across all classes.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.04887](http://arxiv.org/abs/1906.04887)

##### PDF
[http://arxiv.org/pdf/1906.04887](http://arxiv.org/pdf/1906.04887)
