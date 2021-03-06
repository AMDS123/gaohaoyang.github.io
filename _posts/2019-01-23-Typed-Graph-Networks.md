---
layout: post
title: "Typed Graph Networks"
date: 2019-01-23 16:29:24
categories: arXiv_AI
tags: arXiv_AI Attention Ontology Embedding CNN Deep_Learning Relation
author: Pedro Henrique da Costa Avelar, Henrique Lemos, Marcelo de Oliveira Rosa Prates, Marco Gori, Luis Lamb
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, the deep learning community has given growing attention to neural architectures engineered to learn problems in relational domains. Convolutional Neural Networks employ parameter sharing over the image domain, tying the weights of neural connections on a grid topology and thus enforcing the learning of a number of convolutional kernels. By instantiating trainable neural modules and assembling them in varied configurations (apart from grids), one can enforce parameter sharing over graphs, yielding models which can effectively be fed with relational data. In this context, vertices in a graph can be projected into a hyperdimensional real space and iteratively refined over many message-passing iterations in an end-to-end differentiable architecture. Architectures of this family have been referred to with several definitions in the literature, such as Graph Neural Networks, Message-passing Neural Networks, Relational Networks and Graph Networks. In this paper, we revisit the original Graph Neural Network model and show that it generalises many of the recent models, which in turn benefit from the insight of thinking about vertex \textbf{types}. To illustrate the generality of the original model, we present a Graph Neural Network formalisation, which partitions the vertices of a graph into a number of types. Each type represents an entity in the ontology of the problem one wants to learn. This allows - for instance - one to assign embeddings to edges, hyperedges, and any number of global attributes of the graph. As a companion to this paper we provide a Python/Tensorflow library to facilitate the development of such architectures, with which we instantiate the formalisation to reproduce a number of models proposed in the current literature.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.07984](http://arxiv.org/abs/1901.07984)

##### PDF
[http://arxiv.org/pdf/1901.07984](http://arxiv.org/pdf/1901.07984)

