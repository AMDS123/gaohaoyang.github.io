---
layout: post
title: "A GRU-Gated Attention Model for Neural Machine Translation"
date: 2017-04-27 04:25:41
categories: arXiv_CL
tags: arXiv_CL Attention NMT Prediction
author: Biao Zhang, Deyi Xiong, Jinsong Su
mathjax: true
---

* content
{:toc}

##### Abstract
Neural machine translation (NMT) heavily relies on an attention network to produce a context vector for each target word prediction. In practice, we find that context vectors for different target words are quite similar to one another and therefore are insufficient in discriminatively predicting target words. The reason for this might be that context vectors produced by the vanilla attention network are just a weighted sum of source representations that are invariant to decoder states. In this paper, we propose a novel GRU-gated attention model (GAtt) for NMT which enhances the degree of discrimination of context vectors by enabling source representations to be sensitive to the partial translation generated by the decoder. GAtt uses a gated recurrent unit (GRU) to combine two types of information: treating a source annotation vector originally produced by the bidirectional encoder as the history state while the corresponding previous decoder state as the input to the GRU. The GRU-combined information forms a new source annotation vector. In this way, we can obtain translation-sensitive source representations which are then feed into the attention network to generate discriminative context vectors. We further propose a variant that regards a source annotation vector as the current input while the previous decoder state as the history. Experiments on NIST Chinese-English translation tasks show that both GAtt-based models achieve significant improvements over the vanilla attentionbased NMT. Further analyses on attention weights and context vectors demonstrate the effectiveness of GAtt in improving the discrimination power of representations and handling the challenging issue of over-translation.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1704.08430](https://arxiv.org/abs/1704.08430)

##### PDF
[https://arxiv.org/pdf/1704.08430](https://arxiv.org/pdf/1704.08430)

