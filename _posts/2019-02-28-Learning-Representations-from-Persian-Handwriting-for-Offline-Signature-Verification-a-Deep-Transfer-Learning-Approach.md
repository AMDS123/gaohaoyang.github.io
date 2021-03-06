---
layout: post
title: "Learning Representations from Persian Handwriting for Offline Signature Verification, a Deep Transfer Learning Approach"
date: 2019-02-28 08:13:55
categories: arXiv_CV
tags: arXiv_CV Transfer_Learning Classification Recognition
author: Omid Mersa, Farhood Etaati, Saeed Masoudnia, Babak N. Araabi
mathjax: true
---

* content
{:toc}

##### Abstract
Offline Signature Verification (OSV) is a challenging pattern recognition task, especially when it is expected to generalize well on the skilled forgeries that are not available during the training. Its challenges also include small training sample and large intra-class variations. Considering the limitations, we suggest a novel transfer learning approach from Persian handwriting domain to multi-language OSV domain. We train two Residual CNNs on the source domain separately based on two different tasks of word classification and writer identification. Since identifying a person signature resembles identifying ones handwriting, it seems perfectly convenient to use handwriting for the feature learning phase. The learned representation on the more varied and plentiful handwriting dataset can compensate for the lack of training data in the original task, i.e. OSV, without sacrificing the generalizability. Our proposed OSV system includes two steps: learning representation and verification of the input signature. For the first step, the signature images are fed into the trained Residual CNNs. The output representations are then used to train SVMs for the verification. We test our OSV system on three different signature datasets, including MCYT (a Spanish signature dataset), UTSig (a Persian one) and GPDS-Synthetic (an artificial dataset). On UT-SIG, we achieved 9.80% Equal Error Rate (EER) which showed substantial improvement over the best EER in the literature, 17.45%. Our proposed method surpassed state-of-the-arts by 6% on GPDS-Synthetic, achieving 6.81%. On MCYT, EER of 3.98% was obtained which is comparable to the best previously reported results.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.06249](http://arxiv.org/abs/1903.06249)

##### PDF
[http://arxiv.org/pdf/1903.06249](http://arxiv.org/pdf/1903.06249)

