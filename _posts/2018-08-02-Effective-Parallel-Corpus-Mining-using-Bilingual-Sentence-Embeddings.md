---
layout: post
title: "Effective Parallel Corpus Mining using Bilingual Sentence Embeddings"
date: 2018-08-02 17:48:13
categories: arXiv_CL
tags: arXiv_CL Embedding NMT
author: Mandy Guo, Qinlan Shen, Yinfei Yang, Heming Ge, Daniel Cer, Gustavo Hernandez Abrego, Keith Stevens, Noah Constant, Yun-Hsuan Sung, Brian Strope, Ray Kurzweil
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents an effective approach for parallel corpus mining using bilingual sentence embeddings. Our embedding models are trained to produce similar representations exclusively for bilingual sentence pairs that are translations of each other. This is achieved using a novel training method that introduces hard negatives consisting of sentences that are not translations but that have some degree of semantic similarity. The quality of the resulting embeddings are evaluated on parallel corpus reconstruction and by assessing machine translation systems trained on gold vs. mined sentence pairs. We find that the sentence embeddings can be used to reconstruct the United Nations Parallel Corpus at the sentence level with a precision of 48.9% for en-fr and 54.9% for en-es. When adapted to document level matching, we achieve a parallel document matching accuracy that is comparable to the significantly more computationally intensive approach of [Jakob 2010]. Using reconstructed parallel data, we are able to train NMT models that perform nearly as well as models trained on the original data (within 1-2 BLEU).

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1807.11906](https://arxiv.org/abs/1807.11906)

##### PDF
[https://arxiv.org/pdf/1807.11906](https://arxiv.org/pdf/1807.11906)

