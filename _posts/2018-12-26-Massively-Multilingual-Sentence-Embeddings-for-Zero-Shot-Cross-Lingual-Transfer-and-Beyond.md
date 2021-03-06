---
layout: post
title: "Massively Multilingual Sentence Embeddings for Zero-Shot Cross-Lingual Transfer and Beyond"
date: 2018-12-26 18:58:39
categories: arXiv_CV
tags: arXiv_CV Embedding Inference RNN Classification
author: Mikel Artetxe, Holger Schwenk
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce an architecture to learn joint multilingual sentence representations for 93 languages, belonging to more than 30 different language families and written in 28 different scripts. Our system uses a single BiLSTM encoder with a shared BPE vocabulary for all languages, which is coupled with an auxiliary decoder and trained on publicly available parallel corpora. This enables us to learn a classifier on top of the resulting sentence embeddings using English annotated data only, and transfer it to any of the 93 languages without any modification. Our approach sets a new state-of-the-art on zero-shot cross-lingual natural language inference for all the 14 languages in the XNLI dataset but one. We also achieve very competitive results in cross-lingual document classification (MLDoc dataset). Our sentence embeddings are also strong at parallel corpus mining, establishing a new state-of-the-art in the BUCC shared task for 3 of its 4 language pairs. Finally, we introduce a new test set of aligned sentences in 122 languages based on the Tatoeba corpus, and show that our sentence embeddings obtain strong results in multilingual similarity search even for low-resource languages. Our PyTorch implementation, pre-trained encoder and the multilingual test set will be freely available.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1812.10464](https://arxiv.org/abs/1812.10464)

##### PDF
[https://arxiv.org/pdf/1812.10464](https://arxiv.org/pdf/1812.10464)

