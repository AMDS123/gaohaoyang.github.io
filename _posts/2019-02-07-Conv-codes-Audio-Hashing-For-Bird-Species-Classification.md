---
layout: post
title: "Conv-codes: Audio Hashing For Bird Species Classification"
date: 2019-02-07 07:18:39
categories: arXiv_SD
tags: arXiv_SD Sparse Classification
author: Anshul Thakur, Pulkit Sharma, Vinayak Abrol, Padmanabhan Rajan
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we propose a supervised, convex representation based audio hashing framework for bird species classification. The proposed framework utilizes archetypal analysis, a matrix factorization technique, to obtain convex-sparse representations of a bird vocalization. These convex representations are hashed using Bloom filters with non-cryptographic hash functions to obtain compact binary codes, designated as conv-codes. The conv-codes extracted from the training examples are clustered using class-specific k-medoids clustering with Jaccard coefficient as the similarity metric. A hash table is populated using the cluster centers as keys while hash values/slots are pointers to the species identification information. During testing, the hash table is searched to find the species information corresponding to a cluster center that exhibits maximum similarity with the test conv-code. Hence, the proposed framework classifies a bird vocalization in the conv-code space and requires no explicit classifier or reconstruction error calculations. Apart from that, based on min-hash and direct addressing, we also propose a variant of the proposed framework that provides faster and effective classification. The performances of both these frameworks are compared with existing bird species classification frameworks on the audio recordings of 50 different bird species.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.02498](http://arxiv.org/abs/1902.02498)

##### PDF
[http://arxiv.org/pdf/1902.02498](http://arxiv.org/pdf/1902.02498)

