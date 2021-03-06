---
layout: post
title: "Neural source-filter waveform models for statistical parametric speech synthesis"
date: 2019-04-27 02:08:20
categories: arXiv_SD
tags: arXiv_SD Knowledge
author: Xin Wang, Shinji Takaki, Junichi Yamagishi
mathjax: true
---

* content
{:toc}

##### Abstract
Neural waveform models such as WaveNet have demonstrated better performance than conventional vocoders for statistical parametric speech synthesis. As an autoregressive (AR) model, WaveNet is limited by a slow sequential waveform generation process. Some new models that use the inverse-autoregressive flow (IAF) can generate a whole waveform in a one-shot manner. However, these IAF-based models require sequential transformation during training, which severely slows down the training speed. Other models such as Parallel WaveNet and ClariNet bring together the benefits of AR and IAF-based models and train an IAF model by transferring the knowledge from a pre-trained AR teacher to an IAF student without any sequential transformation. However, both models require additional training criteria, and their implementation is prohibitively complicated. 
 We propose a framework for neural source-filter (NSF) waveform modeling without AR nor IAF-based approaches. This framework requires only three components for waveform generation: a source module that generates a sine-based signal as excitation, a non-AR dilated-convolution-based filter module that transforms the excitation into a waveform, and a conditional module that pre-processes the acoustic features for the source and filer modules. This framework minimizes spectral-amplitude distances for model training, which can be efficiently implemented by using short-time Fourier transform routines. Under this framework, we designed three NSF models and compared them with WaveNet. It was demonstrated that the NSF models generated waveforms at least 100 times faster than WaveNet, and the quality of the synthetic speech from the best NSF model was better than or equally good as that from WaveNet.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.12088](http://arxiv.org/abs/1904.12088)

##### PDF
[http://arxiv.org/pdf/1904.12088](http://arxiv.org/pdf/1904.12088)

