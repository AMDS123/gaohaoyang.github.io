---
layout: post
title: "Measuring Patent Claim Generation by Span Relevancy"
date: 2019-08-26 10:59:55
categories: arXiv_CL
tags: arXiv_CL Text_Generation Inference Classification Deep_Learning Language_Model Quantitative
author: Jieh-Sheng Lee, Jieh Hsiang
mathjax: true
---

* content
{:toc}

##### Abstract
Our goal of patent claim generation is to realize "augmented inventing" for inventors by leveraging latest Deep Learning techniques. We envision the possibility of building an "auto-complete" function for inventors to conceive better inventions in the era of artificial intelligence. In order to generate patent claims with good quality, a fundamental question is how to measure it. We tackle the problem from a perspective of claim span relevancy. Patent claim language was rarely explored in the NLP field. It is unique in its own way and contains rich explicit and implicit human annotations. In this work, we propose a span-based approach and a generic framework to measure patent claim generation quantitatively. In order to study the effectiveness of patent claim generation, we define a metric to measure whether two consecutive spans in a generated patent claims are relevant. We treat such relevancy measurement as a span-pair classification problem, following the concept of natural language inference. Technically, the span-pair classifier is implemented by fine-tuning a pre-trained language model. The patent claim generation is implemented by fine-tuning the other pre-trained model. Specifically, we fine-tune a pre-trained Google BERT model to measure the patent claim spans generated by a fine-tuned OpenAI GPT-2 model. In this way, we re-use two of the state-of-the-art pre-trained models in the NLP field. Our result shows the effectiveness of the span-pair classifier after fine-tuning the pre-trained model. It further validates the quantitative metric of span relevancy in patent claim generation. Particularly, we found that the span relevancy ratio measured by BERT becomes lower when the diversity in GPT-2 text generation becomes higher.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.09591](http://arxiv.org/abs/1908.09591)

##### PDF
[http://arxiv.org/pdf/1908.09591](http://arxiv.org/pdf/1908.09591)

