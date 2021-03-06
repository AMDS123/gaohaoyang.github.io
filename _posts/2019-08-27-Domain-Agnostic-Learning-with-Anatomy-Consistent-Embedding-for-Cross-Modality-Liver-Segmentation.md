---
layout: post
title: "Domain-Agnostic Learning with Anatomy-Consistent Embedding for Cross-Modality Liver Segmentation"
date: 2019-08-27 22:44:41
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge Segmentation GAN Embedding Deep_Learning
author: Junlin Yang, Nicha C. Dvornek, Fan Zhang, Juntang Zhuang, Julius Chapiro, MingDe Lin, James S. Duncan
mathjax: true
---

* content
{:toc}

##### Abstract
Domain Adaptation (DA) has the potential to greatly help the generalization of deep learning models. However, the current literature usually assumes to transfer the knowledge from the source domain to a specific known target domain. Domain Agnostic Learning (DAL) proposes a new task of transferring knowledge from the source domain to data from multiple heterogeneous target domains. In this work, we propose the Domain-Agnostic Learning framework with Anatomy-Consistent Embedding (DALACE) that works on both domain-transfer and task-transfer to learn a disentangled representation, aiming to not only be invariant to different modalities but also preserve anatomical structures for the DA and DAL tasks in cross-modality liver segmentation. We validated and compared our model with state-of-the-art methods, including CycleGAN, Task Driven Generative Adversarial Network (TD-GAN), and Domain Adaptation via Disentangled Representations (DADR). For the DA task, our DALACE model outperformed CycleGAN, TD-GAN ,and DADR with DSC of 0.847 compared to 0.721, 0.793 and 0.806. For the DAL task, our model improved the performance with DSC of 0.794 from 0.522, 0.719 and 0.742 by CycleGAN, TD-GAN, and DADR. Further, we visualized the success of disentanglement, which added human interpretability of the learned meaningful representations. Through ablation analysis, we specifically showed the concrete benefits of disentanglement for downstream tasks and the role of supervision for better disentangled representation with segmentation consistency to be invariant to domains with the proposed Domain-Agnostic Module (DAM) and to preserve anatomical information with the proposed Anatomy-Preserving Module (APM).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.10489](http://arxiv.org/abs/1908.10489)

##### PDF
[http://arxiv.org/pdf/1908.10489](http://arxiv.org/pdf/1908.10489)

