---
layout: post
title: "Deep Reasoning Networks: Thinking Fast and Slow"
date: 2019-06-03 15:09:57
categories: arXiv_AI
tags: arXiv_AI Knowledge Optimization Deep_Learning Gradient_Descent
author: Di Chen, Yiwei Bai Wenting Zhao, Sebastian Ament, John Gregoire, Carla Gomes
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce Deep Reasoning Networks (DRNets), an end-to-end framework that combines deep learning with reasoning for solving complex tasks, typically in an unsupervised or weakly-supervised setting. DRNets exploit problem structure and prior knowledge by tightly combining logic and constraint reasoning with stochastic-gradient-based neural network optimization. We illustrate the power of DRNets on de-mixing overlapping hand-written Sudokus (Multi-MNIST-Sudoku) and on a substantially more complex task in scientific discovery that concerns inferring crystal structures of materials from X-ray diffraction data under thermodynamic rules (Crystal-Structure-Phase-Mapping). At a high level, DRNets encode a structured latent space of the input data, which is constrained to adhere to prior knowledge by a reasoning module. The structured latent encoding is used by a generative decoder to generate the targeted output. Finally, an overall objective combines responses from the generative decoder (thinking fast) and the reasoning module (thinking slow), which is optimized using constraint-aware stochastic gradient descent. We show how to encode different tasks as DRNets and demonstrate DRNets' effectiveness with detailed experiments: DRNets significantly outperform the state of the art and experts' capabilities on Crystal-Structure-Phase-Mapping, recovering more precise and physically meaningful crystal structures. On Multi-MNIST-Sudoku, DRNets perfectly recovered the mixed Sudokus' digits, with 100% digit accuracy, outperforming the supervised state-of-the-art MNIST de-mixing models. Finally, as a proof of concept, we also show how DRNets can solve standard combinatorial problems -- 9-by-9 Sudoku puzzles and Boolean satisfiability problems (SAT), outperforming other specialized deep learning models. DRNets are general and can be adapted and expanded to tackle other tasks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.00855](http://arxiv.org/abs/1906.00855)

##### PDF
[http://arxiv.org/pdf/1906.00855](http://arxiv.org/pdf/1906.00855)

