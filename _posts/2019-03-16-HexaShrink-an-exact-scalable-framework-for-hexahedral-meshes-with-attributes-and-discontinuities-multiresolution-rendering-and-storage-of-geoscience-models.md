---
layout: post
title: "HexaShrink, an exact scalable framework for hexahedral meshes with attributes and discontinuities: multiresolution rendering and storage of geoscience models"
date: 2019-03-16 10:24:22
categories: arXiv_CV
tags: arXiv_CV
author: Jean-Luc Peyrot, Laurent Duval, Fr&#xe9;d&#xe9;ric Payan, Lauriane Bouard, L&#xe9;na&#xef;c Chizat, S&#xe9;bastien Schneider, Marc Antonini
mathjax: true
---

* content
{:toc}

##### Abstract
With huge data acquisition progresses realized in the past decades and acquisition systems now able to produce high resolution grids and point clouds, the digitization of physical terrains becomes increasingly more precise. Such extreme quantities of generated and modeled data greatly impact computational performances on many levels of high-performance computing (HPC): storage media, memory requirements, transfer capability, and finally simulation interactivity, necessary to exploit this instance of big data. Efficient representations and storage are thus becoming "enabling technologies'' in HPC experimental and simulation science. We propose HexaShrink, an original decomposition scheme for structured hexahedral volume meshes. The latter are used for instance in biomedical engineering, materials science, or geosciences. HexaShrink provides a comprehensive framework allowing efficient mesh visualization and storage. Its exactly reversible multiresolution decomposition yields a hierarchy of meshes of increasing levels of details, in terms of either geometry, continuous or categorical properties of cells. Starting with an overview of volume meshes compression techniques, our contribution blends coherently different multiresolution wavelet schemes in different dimensions. It results in a global framework preserving discontinuities (faults) across scales, implemented as a fully reversible upscaling at different resolutions. Experimental results are provided on meshes of varying size and complexity. They emphasize the consistency of the proposed representation, in terms of visualization, attribute downsampling and distribution at different resolutions. Finally, HexaShrink yields gains in storage space when combined to lossless compression techniques.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.07614](http://arxiv.org/abs/1903.07614)

##### PDF
[http://arxiv.org/pdf/1903.07614](http://arxiv.org/pdf/1903.07614)

