---
title: A Simple Baseline for Adversarial Domain Adaptation-based Unsupervised
  Flood Forecasting
abstract: "Flood disasters cause enormous social and economic losses. However,
  both traditional physical models and learning-based flood forecasting models
  require massive historical flood data to train the model parameters. When come
  to some new site that does not have sufficient historical data, the model
  performance will drop dramatically due to overfitting. This technical report
  presents a Flood Domain Adaptation Network (FloodDAN), a baseline of applying
  Unsupervised Domain Adaptation (UDA) to the flood forecasting problem.
  Specifically, training of FloodDAN includes two stages: in the first stage, we
  train a rainfall encoder and a prediction head to learn general transferable
  hydrological knowledge on large-scale source domain data; in the second stage,
  we transfer the knowledge in the pretrained encoder into the rainfall encoder
  of target domain through adversarial domain alignment. During inference, we
  utilize the target domain rainfall encoder trained in the second stage and the
  prediction head trained in the first stage to get flood forecasting
  predictions. Experimental results on Tunxi and Changhua flood dataset show
  that FloodDAN can perform flood forecasting effectively with zero target
  domain supervision. The performance of the FloodDAN is on par with supervised
  models that uses 450-500 hours of supervision."
slides: ""
url_pdf: publication/arxiv2022simple/A_Simple_Baseline_for_Adversarial_Domain_Adaptation_based_Unsupervised_Flood_Forecasting.pdf
publication_types:
  - "3"
authors:
  - Delong Chen
  - Ruizhi Zhou
  - Yanling Pan
  - Fan Liu
publication: Technical Report. [[ArXiv]](https://arxiv.org/abs/2206.08105)
featured: true
tags:
  - Deep Learning
  - Hydrological Forecasting
projects:
  - 数据驱动的水文时间序列预测
summary: This technical report presents a Flood Domain Adaptation Network
  (FloodDAN), the first baseline of unsupervised flood forecasting problem.
url_dataset: ""
url_project: ""
publication_short: Technical Report
url_source: ""
url_video: ""
date: 2022-06-17T00:00:00Z
url_slides: ""
links: null
image:
  preview_only: false
publishDate: 2022-06-17T00:00:00Z
url_poster: ""
url_code: ""
doi: ""
---
