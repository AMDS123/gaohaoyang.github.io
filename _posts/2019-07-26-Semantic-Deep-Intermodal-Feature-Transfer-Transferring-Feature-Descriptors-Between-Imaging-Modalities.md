---
layout: post
title: "Semantic Deep Intermodal Feature Transfer: Transferring Feature Descriptors Between Imaging Modalities"
date: 2019-07-26 08:42:38
categories: arXiv_CV
tags: arXiv_CV CNN Prediction
author: Sebastian P. Kleinschmidt, Bernardo Wagner
mathjax: true
---

* content
{:toc}

##### Abstract
Under difficult environmental conditions, the view of RGB cameras may be restricted by fog, dust or difficult lighting situations. Because thermal cameras visualize thermal radiation, they are not subject to the same limitations as RGB cameras. However, because RGB and thermal imaging differ significantly in appearance, common, state-of-the-art feature descriptors are unsuitable for intermodal feature matching between these imaging modalities. As a consequence, visual maps created with an RGB camera can currently not be used for localization using a thermal camera. In this paper, we introduce the Semantic Deep Intermodal Feature Transfer (Se-DIFT), an approach for transferring image feature descriptors from the visual to the thermal spectrum and vice versa. For this purpose, we predict potential feature appearance in varying imaging modalities using a deep convolutional encoder-decoder architecture in combination with a global feature vector. Since the representation of a thermal image is not only affected by features which can be extracted from an RGB image, we introduce the global feature vector which augments the auto encoder's coding. The global feature vector contains additional information about the thermal history of a scene which is automatically extracted from external data sources. By augmenting the encoder's coding, we decrease the L1 error of the prediction by more than 7% compared to the prediction of a traditional U-Net architecture. To evaluate our approach, we match image feature descriptors detected in RGB and thermal images using Se-DIFT. Subsequently, we make a competitive comparison on the intermodal transferability of SIFT, SURF, and ORB features using our approach.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.11436](http://arxiv.org/abs/1907.11436)

##### PDF
[http://arxiv.org/pdf/1907.11436](http://arxiv.org/pdf/1907.11436)

