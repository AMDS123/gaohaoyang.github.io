---
layout: post
title: "MILDNet: A Lightweight Single Scaled Deep Ranking Architecture"
date: 2019-03-03 13:26:37
categories: arXiv_AI
tags: arXiv_AI Image_Retrieval Embedding Inference
author: Anirudha Vishvakarma
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-scale deep CNN architecture [1, 2, 3] successfully captures both fine and coarse level image descriptors for visual similarity task, but they come up with expensive memory overhead and latency. In this paper, we propose a competing novel CNN architecture, called MILDNet, which merits by being vastly compact (about 3 times). Inspired by the fact that successive CNN layers represent the image with increasing levels of abstraction, we compressed our deep ranking model to a single CNN by coupling activations from multiple intermediate layers along with the last layer. Trained on the famous Street2shop dataset [4], we demonstrate that our approach performs as good as the current state-of-the-art models with only one third of the parameters, model size, training time and significant reduction in inference time. The significance of intermediate layers on image retrieval task has also been shown to be performing on popular datasets Holidays, Oxford, Paris [5]. So even though our experiments are done on ecommerce domain, it is applicable to other domains as well. We further did an ablation study to validate our hypothesis by checking the impact on adding each intermediate layer. With this we also present two more useful variants of MILDNet, a mobile model (12 times smaller) for on-edge devices and a compactly featured model (512-d feature embeddings) for systems with less RAMs and to reduce the ranking cost. Further we present an intuitive way to automatically create a tailored in-house triplet training dataset, which is very hard to create manually. This solution too can also be deployed as an all-inclusive visual similarity solution. Finally, we present our entire production level architecture which currently powers visual similarity at Fynd.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.00905](http://arxiv.org/abs/1903.00905)

##### PDF
[http://arxiv.org/pdf/1903.00905](http://arxiv.org/pdf/1903.00905)

