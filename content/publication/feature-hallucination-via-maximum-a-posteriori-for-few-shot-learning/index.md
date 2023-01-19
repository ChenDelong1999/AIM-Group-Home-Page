---
title: Feature hallucination via Maximum A Posteriori for few-shot learning
publication_types:
  - "2"
authors:
  - Jiaying Wu
  - Ning Dong
  - 刘凡
  - 杨赛
  - Jinglu Hu
doi: https://doi.org/10.1016/j.knosys.2021.107129
publication: Knowledge-Based Systems
publication_short: "Knowl. Based Syst. "
abstract: Few-shot learning aims to train an effective classifier in a small
  data regime. Due to the scarcity of training samples (usually as small as 1 or
  5), traditional deep learning solutions often suffer from overfitting. To
  address this issue, an intuitive idea is to augment or hallucinate sufficient
  training data. For this purpose, in this paper, we propose a simple yet
  effective method to build a model for novel categories with few samples.
  Specifically, we assume that each category in the base set follows a Gaussian
  distribution, so that we can employ Maximum A Posteriori (MAP) to estimate the
  distribution of a novel category with even one example. To achieve this goal,
  we first transform each base category into Gaussian form with power
  transformation for MAP estimation. Then, we estimate the Gaussian mean of the
  novel category under the Gaussian prior given few samples from it. Finally,
  each novel category is represented by a unique Gaussian distribution, where
  sufficient trainable features can be sampled to obtain a highly accurate
  classifier for final predictions. Experimental results on four few-shot
  benchmarks show that it significantly outperforms the baseline methods on both
  1- and 5-shot tasks. Extensive results on cross-domain tasks and visualization
  of estimated feature distribution also demonstrate its
draft: false
featured: false
tags:
  - Few-shot learning
  - Maximum A Posteriori
  - Feature hallucination
  - Gaussian prior
projects:
  - 视觉小样本学习
image:
  filename: featured.jpg
  focal_point: Smart
  preview_only: false
  caption: The overall framework of our method. In the base training stage, we use
    all the classes in the base set to obtain the prior knowledge required for
    MAP estimation. The features extracted from the base and novel classes are
    all transformed into Gaussian form, so that each class is represented by the
    corresponding mean vector and covariance matrix. With the base mean and
    covariance, we conduct a MAP estimation for one example from novel classes.
    Finally, based on the estimation, we compute the distribution of support set
    in novel classes and sample features from the distribution to train a
    logistic regression model for classification.
  alt_text: The overall framework of our method. In the base training stage, we
    use all the classes in the base set to obtain the prior knowledge required
    for MAP estimation. The features extracted from the base and novel classes
    are all transformed into Gaussian form, so that each class is represented by
    the corresponding mean vector and covariance matrix. With the base mean and
    covariance, we conduct a MAP estimation for one example from novel classes.
    Finally, based on the estimation, we compute the distribution of support set
    in novel classes and sample features from the distribution to train a
    logistic regression model for classification.
summary: Few-shot learning aims to train an effective classifier in a small data
  regime. Due to the scarcity of training samples (usually as small as 1 or 5),
  traditional deep learning solutions often suffer from overfitting. To address
  this issue, an intuitive idea is to augment or hallucinate sufficient training
  data. For this purpose, in this paper, we propose a simple yet effective
  method to build a model for novel categories with few samples.
date: 2021-05-21T14:02:45.425Z
---
