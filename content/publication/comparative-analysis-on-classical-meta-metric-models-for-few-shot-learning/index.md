---
title: Comparative Analysis on Classical Meta-Metric Models for Few-Shot Learning
publication_types:
  - "2"
authors:
  - 杨赛
  - 刘凡
  - Ning Dong
  - Jiaying Wu
doi: https://doi.org/10.1109/ACCESS.2020.3008684
publication: IEEE Access
publication_short: IEEE Access
abstract: Few-shot learning are methods and scenarios learned from a small
  amount of labeled data. While recent meta-metric learning methods have made
  significant progress, there are still questions about what is the key point of
  these methods and how they work. To address these problems, in this paper, we
  evaluate the effects of different parts in classical models. To be specific,
  we 1) use four typical networks AlexNet, VGG16, GoogLeNet, and ResNet50 to
  replace the original feature extraction part in the Matching Network,
  Prototypical Network, and Relation Network, and compare the best results with
  17 state-of-the-art meta-metric learning algorithms. 2) fix the feature
  extraction part of the Matching Network, Prototypical Network and Relation
  Network, and change the similarity measurement part of each into L1, L2,
  Cosine. 3) conduct above three models on datasets of different granularity.
  The experimental results show that for all models evaluated, the addition of
  non-pretrained networks will make the classification results worse, which
  shows that it is easy to overfit when using deep networks for few-shot
  learning. Changes in similarity measurement methods have a significant impact
  on results, which shows the importance to choose a suitable measurement.
  Moreover, there are differences in performance on different granularity
  datasets.
draft: false
featured: false
tags:
  - Few-shot
  - meta-metric learning
  - feature extraction
  - similarity measurement
  - comparative analysis
categories: []
projects:
  - 视觉小样本学习
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
  caption: Structure of matching network
  alt_text: Structure of matching network
summary: Few-shot learning are methods and scenarios learned from a small amount
  of labeled data. While recent meta-metric learning methods have made
  significant progress, there are still questions about what is the key point of
  these methods and how they work. To address these problems, in this paper, we
  evaluate the effects of different parts in classical models.
date: 2020-07-13T14:07:28.740Z
---
