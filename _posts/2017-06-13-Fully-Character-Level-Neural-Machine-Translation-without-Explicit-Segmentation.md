---
layout: post
title: "Fully Character-Level Neural Machine Translation without Explicit Segmentation"
date: 2017-06-13 03:32:34
categories: arXiv_CL
tags: arXiv_CL Segmentation CNN NMT
author: Jason Lee, Kyunghyun Cho, Thomas Hofmann
mathjax: true
---

* content
{:toc}

##### Abstract
Most existing machine translation systems operate at the level of words, relying on explicit segmentation to extract tokens. We introduce a neural machine translation (NMT) model that maps a source character sequence to a target character sequence without any segmentation. We employ a character-level convolutional network with max-pooling at the encoder to reduce the length of source representation, allowing the model to be trained at a speed comparable to subword-level models while capturing local regularities. Our character-to-character model outperforms a recently proposed baseline with a subword-level encoder on WMT'15 DE-EN and CS-EN, and gives comparable performance on FI-EN and RU-EN. We then demonstrate that it is possible to share a single character-level encoder across multiple languages by training a model on a many-to-one translation task. In this multilingual setting, the character-level encoder significantly outperforms the subword-level encoder on all the language pairs. We observe that on CS-EN, FI-EN and RU-EN, the quality of the multilingual character-level translation even surpasses the models specifically trained on that language pair alone, both in terms of BLEU score and human judgment.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1610.03017](https://arxiv.org/abs/1610.03017)

##### PDF
[https://arxiv.org/pdf/1610.03017](https://arxiv.org/pdf/1610.03017)

