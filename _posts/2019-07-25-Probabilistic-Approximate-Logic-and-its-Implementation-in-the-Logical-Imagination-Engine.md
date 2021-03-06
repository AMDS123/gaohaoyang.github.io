---
layout: post
title: "Probabilistic Approximate Logic and its Implementation in the Logical Imagination Engine"
date: 2019-07-25 22:13:24
categories: arXiv_AI
tags: arXiv_AI Knowledge Inference Gradient_Descent
author: Mark-Oliver Stehr, Minyoung Kim, Carolyn L. Talcott, Merrill Knapp, Akos Vertes
mathjax: true
---

* content
{:toc}

##### Abstract
In spite of the rapidly increasing number of applications of machine learning in various domains, a principled and systematic approach to the incorporation of domain knowledge in the engineering process is still lacking and ad hoc solutions that are difficult to validate are still the norm in practice, which is of growing concern not only in mission-critical applications. 
 In this note, we introduce Probabilistic Approximate Logic (PALO) as a logic based on the notion of mean approximate probability to overcome conceptual and computational difficulties inherent to strictly probabilistic logics. The logic is approximate in several dimensions. Logical independence assumptions are used to obtain approximate probabilities, but by averaging over many instances of formulas a useful estimate of mean probability with known confidence can usually be obtained. To enable efficient computational inference, the logic has a continuous semantics that reflects only a subset of the structural properties of classical logic, but this imprecision can be partly compensated by richer theories obtained by classical inference or other means. Computational inference, which refers to the construction of models and validation of logical properties, is based on Stochastic Gradient Descent (SGD) and Markov Chain Monte Carlo (MCMC) techniques and hence another dimension where approximations are involved. 
 We also present the Logical Imagination Engine (LIME), a prototypical implementation of PALO based on TensorFlow. Albeit not limited to the biological domain, we illustrate its operation in a quite substantial bioinformatics machine learning application concerned with network synthesis and analysis in a recent DARPA project.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.11321](http://arxiv.org/abs/1907.11321)

##### PDF
[http://arxiv.org/pdf/1907.11321](http://arxiv.org/pdf/1907.11321)

