---
layout: post
title: "Non-Parallel Sequence-to-Sequence Voice Conversion with Disentangled Linguistic and Speaker Representations"
date: 2019-06-25 13:33:47
categories: arXiv_SD
tags: arXiv_SD Adversarial Embedding
author: Jing-Xuan Zhang, Zhen-Hua Ling, Li-Rong Dai
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, a method for non-parallel sequence-to-sequence (seq2seq) voice conversion is presented. Disentangled linguistic and speaker representations are learned in proposed method. Our model is built under the framework of encoder-decoder. Encoders are used to extract hidden representations, which the decoder uses for recovering acoustic features. For learning disentangled linguistic representations, we proposed two strategies. First, additional text inputs are introduced for generating embeddings with audio inputs jointly. And hidden embeddings of text inputs are used as the reference for those of audio inputs. Second, an adversarial training method is adopted to further wipe out speaker related descriptions from the linguistic embeddings of audio signals. Meanwhile, speaker representations are extracted by a speaker encoder. Both the encoder for extracting linguistic representations from audio and the decoder themselves are built with seq2seq network. Therefore there is no constrain of the frame-by-frame conversion in our proposed method. For training the model, a strategy that consists of two stages is adopted. At the first stage, our model is pre-trained on a multi-speaker dataset. Then it is finetuned on the dataset of a specific conversion pair at the second stage. Experiments were conducted to compare the proposed method with both parallel and non-parallel baselines. The experimental results showed that our method obtained higher similarity and naturalness compared to the top rank method in Voice Conversion Challenge 2018, which is a non-parallel baseline. And the performance of proposed method was closed to the state-of-art seq2seq based parallel baseline. Ablation tests were also conducted to validate the proposed strategies for disentangling and pre-training.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.10508](http://arxiv.org/abs/1906.10508)

##### PDF
[http://arxiv.org/pdf/1906.10508](http://arxiv.org/pdf/1906.10508)

