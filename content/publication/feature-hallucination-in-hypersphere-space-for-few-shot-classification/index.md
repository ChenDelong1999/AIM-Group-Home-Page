---
title: Feature hallucination in hypersphere space for few-shot classification
publication_types:
  - "2"
authors:
  - 杨赛
  - 刘凡
  - 陈峙宇
doi: https://doi.org/10.1049/ipr2.12579
publication: " IET Image Process"
publication_short: " IET Image Process"
abstract: Few-shot classification (FSC) targeting at classifying unseen classes
  with few labelled samples is still a challenging task. Recent works show that
  transfer-learning based approaches are competitive with meta-learning ones,
  which usually pre-train a convolutional neural networks (CNN)-based network
  using cross-entropy (CE) loss and throw away the last layer to post-process
  the novel classes. Hereby, they still suffer the issue of getting a more
  transferable extractor and lacking enough labelled novel samples. Thus, the
  authors propose the algorithm of feature hallucination in hypersphere space
  (FHHS) for FSC. On the first stage, the authors pre-train a more transferable
  feature extractor using a hypersphere loss (HL), which supplies CE with
  supervised contrastive (SC) loss and self-supervised loss (SSL), in which SC
  can map the base and novel images onto the hypersphere space densely. On the
  second stage, the authors generate new samples for unseen classes using their
  novel algorithm of synthetic novel sampling with the base (SNSB), which
  linearly interpolate between each novel class prototype and its K nearest
  neighbour base class prototypes. Comprehensive experiments on multiple popular
  FSC demonstrate that HL loss can enhance the performance of backbone network
  and the authors’ feature hallucination method is superior to the existing
  hallucination-based methods.
draft: false
featured: false
tags:
  - few-shot
  - deep-learning
  - computer-vision
projects:
  - 视觉小样本学习
image:
  filename: featured.jpg
  focal_point: Smart
  preview_only: false
date: 2022-07-20T13:42:01.192Z
---
