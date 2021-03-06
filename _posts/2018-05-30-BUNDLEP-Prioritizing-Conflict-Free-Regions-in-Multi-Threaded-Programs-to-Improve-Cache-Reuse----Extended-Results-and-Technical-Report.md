---
layout: post
title: "BUNDLEP: Prioritizing Conflict Free Regions in Multi-Threaded Programs to Improve Cache Reuse -- Extended Results and Technical Report"
date: 2018-05-30 15:42:05
categories: arXiv_CV
tags: arXiv_CV Knowledge
author: Corey Tessler, Nathan Fisher
mathjax: true
---

* content
{:toc}

##### Abstract
In BUNDLE: Real-Time Multi-Threaded Scheduling to Reduce Cache Contention, Tessler and Fisher propose a scheduling mechanism and combined worst-case execution time calculation method that treats the instruction cache as a beneficial resource shared between threads. Object analysis produces a worst-case execution time bound and separates code segments into regions. Threads are dynamically placed in bundles as- sociated with regions at run time by the BUNDLE scheduling algorithm where they benefit from shared cache values. In the evaluation of the previous work, tasks were created with a predetermined worst-case execution time path through the control flow graph. Apriori knowledge of the worst-case path is an impractical restriction on any analysis. At the time, the only other solution available was an all-paths search of the graph, which is an equally impractical approach due to its complexity. The primary focus of this work is to build upon BUNDLE, expanding its applicability beyond a proof of concept. We present a complete a worst-case execution time calculation method that includes thread level context switch costs, operating on real programs, with representative architecture parameters, and compare our results to those produced by Heptane's state of the art method. To these ends, we propose a modification to the BUNDLE scheduling algorithm called BUNDLEP. Bundles are assigned priorities that enforce an ordered flow of threads through the control flow graph -- avoiding the need for multiple all-paths searches through the graph. In many cases, our evaluation shows a run-time and analytical benefit for BUNLDEP compared to serialized thread execution and state of the art WCET analysis.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1805.12041](https://arxiv.org/abs/1805.12041)

##### PDF
[https://arxiv.org/pdf/1805.12041](https://arxiv.org/pdf/1805.12041)

