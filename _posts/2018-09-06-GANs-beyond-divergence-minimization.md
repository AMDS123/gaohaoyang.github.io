---
layout: post
title: "GANs beyond divergence minimization"
date: 2018-09-06 18:00:26
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Alexia Jolicoeur-Martineau
mathjax: true
---

* content
{:toc}

##### Abstract
Generative adversarial networks (GANs) can be interpreted as an adversarial game between two players, a discriminator D and a generator G, in which D learns to classify real from fake data and G learns to generate realistic data by "fooling" D into thinking that fake data is actually real data. Currently, a dominating view is that G actually learns by minimizing a divergence given that the general objective function is a divergence when D is optimal. However, this view has been challenged due to inconsistencies between theory and practice. In this paper, we discuss of the properties associated with most loss functions for G (e.g., saturating/non-saturating f-GAN, LSGAN, WGAN, etc.). We show that these loss functions are not divergences and do not have the same equilibrium as expected of divergences. This suggests that G does not need to minimize the same objective function as D maximize, nor maximize the objective of D after swapping real data with fake data (non-saturating GAN) but can instead use a wide range of possible loss functions to learn to generate realistic data. We define GANs through two separate and independent D maximization and G minimization steps. We generalize the generator step to four new classes of loss functions, most of which are actual divergences (while traditional G loss functions are not). We test a wide variety of loss functions from these four classes on a synthetic dataset and on CIFAR-10. We observe that most loss functions converge well and provide comparable data generation quality to non-saturating GAN, LSGAN, and WGAN-GP generator loss functions, whether we use divergences or non-divergences. These results suggest that GANs do not conform well to the divergence minimization theory and form a much broader range of models than previously assumed.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1809.02145](https://arxiv.org/abs/1809.02145)

##### PDF
[https://arxiv.org/pdf/1809.02145](https://arxiv.org/pdf/1809.02145)

