---
layout: post
title: "Commonsense for Generative Multi-Hop Question Answering Tasks"
date: 2019-06-01 03:50:14
categories: arXiv_AI
tags: arXiv_AI Knowledge QA Attention Prediction Relation
author: Lisa Bauer, Yicheng Wang, Mohit Bansal
mathjax: true
---

* content
{:toc}

##### Abstract
Reading comprehension QA tasks have seen a recent surge in popularity, yet most works have focused on fact-finding extractive QA. We instead focus on a more challenging multi-hop generative task (NarrativeQA), which requires the model to reason, gather, and synthesize disjoint pieces of information within the context to generate an answer. This type of multi-step reasoning also often requires understanding implicit relations, which humans resolve via external, background commonsense knowledge. We first present a strong generative baseline that uses a multi-attention mechanism to perform multiple hops of reasoning and a pointer-generator decoder to synthesize the answer. This model performs substantially better than previous generative models, and is competitive with current state-of-the-art span prediction models. We next introduce a novel system for selecting grounded multi-hop relational commonsense information from ConceptNet via a pointwise mutual information and term-frequency based scoring function. Finally, we effectively use this extracted commonsense information to fill in gaps of reasoning between context hops, using a selectively-gated attention mechanism. This boosts the model's performance significantly (also verified via human evaluation), establishing a new state-of-the-art for the task. We also show promising initial results of the generalizability of our background knowledge enhancements by demonstrating some improvement on QAngaroo-WikiHop, another multi-hop reasoning dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.06309](http://arxiv.org/abs/1809.06309)

##### PDF
[http://arxiv.org/pdf/1809.06309](http://arxiv.org/pdf/1809.06309)

