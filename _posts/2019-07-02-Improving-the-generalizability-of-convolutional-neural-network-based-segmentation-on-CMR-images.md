---
layout: post
title: "Improving the generalizability of convolutional neural network-based segmentation on CMR images"
date: 2019-07-02 09:57:15
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Chen Chen, Wenjia Bai, Rhodri H. Davies, Anish N. Bhuva, Charlotte Manisty, James C. Moon, Nay Aung, Aaron M. Lee, Mihir M. Sanghvi, Kenneth Fung, Jose Miguel Paiva, Steffen E. Petersen, Elena Lukaschuk, Stefan K. Piechnik, Stefan Neubauer, Daniel Rueckert
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural network (CNN) based segmentation methods provide an efficient and automated way for clinicians to assess the structure and function of the heart in cardiac MR images. While CNNs can generally perform the segmentation tasks with high accuracy when training and test images come from the same domain (e.g. same scanner or site), their performance often degrades dramatically on images from different scanners or clinical sites. We propose a simple yet effective way for improving the network generalization ability by carefully designing data normalization and augmentation strategies to accommodate common scenarios in multi-site, multi-scanner clinical imaging data sets. We demonstrate that a neural network trained on a single-site single-scanner dataset from the UK Biobank can be successfully applied to segmenting cardiac MR images across different sites and different scanners without substantial loss of accuracy. Specifically, the method was trained on a large set of 3,975 subjects from the UK Biobank. It was then directly tested on 600 different subjects from the UK Biobank for intra-domain testing and two other sets for cross-domain testing: the ACDC dataset (100 subjects, 1 site, 2 scanners) and the BSCMR-AS dataset (599 subjects, 6 sites, 9 scanners). The proposed method produces promising segmentation results on the UK Biobank test set which are comparable to previously reported values in the literature, while also performing well on cross-domain test sets, achieving a mean Dice metric of 0.90 for the left ventricle, 0.81 for the myocardium and 0.82 for the right ventricle on the ACDC dataset; and 0.89 for the left ventricle, 0.83 for the myocardium on the BSCMR-AS dataset. The proposed method offers a potential solution to improve CNN-based model generalizability for the cross-scanner and cross-site cardiac MR image segmentation task.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.01268](http://arxiv.org/abs/1907.01268)

##### PDF
[http://arxiv.org/pdf/1907.01268](http://arxiv.org/pdf/1907.01268)

