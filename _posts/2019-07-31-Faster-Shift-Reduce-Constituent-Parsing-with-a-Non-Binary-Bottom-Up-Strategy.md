---
layout: post
title: "Faster Shift-Reduce Constituent Parsing with a Non-Binary, Bottom-Up Strategy"
date: 2019-07-31 13:11:10
categories: arXiv_CL
tags: arXiv_CL
author: Daniel Fern&#xe1;ndez-Gonz&#xe1;lez, Carlos G&#xf3;mez-Rodr&#xed;guez
mathjax: true
---

* content
{:toc}

##### Abstract
An increasingly wide range of artificial intelligence applications rely on syntactic information to process and extract meaning from natural language text or speech, with constituent trees being one of the most widely used syntactic formalisms. To produce these phrase-structure representations from sentences in natural language, shift-reduce constituent parsers have become one of the most efficient approaches. Increasing their accuracy and speed is still one of the main objectives pursued by the research community so that artificial intelligence applications that make use of parsing outputs, such as machine translation or voice assistant services, can improve their performance. With this goal in mind, we propose in this article a novel non-binary shift-reduce algorithm for constituent parsing. Our parser follows a classical bottom-up strategy but, unlike others, it straightforwardly creates non-binary branchings with just one Reduce transition, instead of requiring prior binarization or a sequence of binary transitions, allowing its direct application to any language without the need of further resources such as percolation tables. As a result, it uses fewer transitions per sentence than existing transition-based constituent parsers, becoming the fastest such system and, as a consequence, speeding up downstream applications. Using static oracle training and greedy search, the accuracy of this novel approach is on par with state-of-the-art transition-based constituent parsers and outperforms all top-down and bottom-up greedy shift-reduce systems on the Wall Street Journal section from the English Penn Treebank and the Penn Chinese Treebank. Additionally, we develop a dynamic oracle for training the proposed transition-based algorithm, achieving further improvements in both benchmarks and obtaining the best accuracy to date on the Penn Chinese Treebank among greedy shift-reduce parsers.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1804.07961](http://arxiv.org/abs/1804.07961)

##### PDF
[http://arxiv.org/pdf/1804.07961](http://arxiv.org/pdf/1804.07961)

