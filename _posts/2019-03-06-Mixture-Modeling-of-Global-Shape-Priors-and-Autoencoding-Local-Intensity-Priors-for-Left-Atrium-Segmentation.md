---
layout: post
title: "Mixture Modeling of Global Shape Priors and Autoencoding Local Intensity Priors for Left Atrium Segmentation"
date: 2019-03-06 23:24:08
categories: arXiv_CV
tags: arXiv_CV Segmentation Optimization
author: Tim Sodergren, Riddhish Bhalodia, Ross Whitaker, Joshua Cates, Nassir Marrouche, Shireen Elhabian
mathjax: true
---

* content
{:toc}

##### Abstract
Difficult image segmentation problems, for instance left atrium MRI, can be addressed by incorporating shape priors to find solutions that are consistent with known objects. Nonetheless, a single multivariate Gaussian is not an adequate model in cases with significant nonlinear shape variation or where the prior distribution is multimodal. Nonparametric density estimation is more general, but has a ravenous appetite for training samples and poses serious challenges in optimization, especially in high dimensional spaces. Here, we propose a maximum-a-posteriori formulation that relies on a generative image model by incorporating both local intensity and global shape priors. We use deep autoencoders to capture the complex intensity distribution while avoiding the careful selection of hand-crafted features. We formulate the shape prior as a mixture of Gaussians and learn the corresponding parameters in a high-dimensional shape space rather than pre-projecting onto a low-dimensional subspace. In segmentation, we treat the identity of the mixture component as a latent variable and marginalize it within a generalized expectation-maximization framework. We present a conditional maximization-based scheme that alternates between a closed-form solution for component-specific shape parameters that provides a global update-based optimization strategy, and an intensity-based energy minimization that translates the global notion of a nonlinear shape prior into a set of local penalties. We demonstrate our approach on the left atrial segmentation from gadolinium-enhanced MRI, which is useful in quantifying the atrial geometry in patients with atrial fibrillation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.06260](http://arxiv.org/abs/1903.06260)

##### PDF
[http://arxiv.org/pdf/1903.06260](http://arxiv.org/pdf/1903.06260)

