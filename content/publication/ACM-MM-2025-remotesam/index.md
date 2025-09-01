---
title: "RemoteSAM: Towards Segment Anything for Earth Observation"
publication_types:
  - "1" 
authors:
  - Liang Yao
  - Fan Liu
  - Delong Chen
  - Chuanyi Zhang
  - Yijun Wang
  - Ziyun Chen
  - Wei Xu
  - Shimin Di
  - Yuhui Zheng

publication: ACM International Conference on Multimedia
publication_short: "ACM MM 2025"

url_pdf: publication/ACM-MM-2025-remotesam/remotesam.pdf

abstract: We aim to develop a robust yet flexible visual foundation model for Earth observation. It should possess strong capabilities in recognizing and localizing diverse visual targets while providing compatibility with various input-output interfaces required across different task scenarios. Current systems cannot meet these requirements, as they typically utilize task-specific architecture trained on narrow data domains with limited semantic coverage. Our study addresses these limitations from two aspects: data and modeling. We first introduce an automatic data engine that enjoys significantly better scalability compared to previous human annotation or rule-based approaches. It has enabled us to create the largest dataset of its kind to date, comprising 270K image-text-mask triplets covering an unprecedented range of diverse semantic categories and attribute specifications. Based on this data foundation, we further propose a task unification paradigm that centers around referring expression segmentation. It effectively handles a wide range of vision-centric perception tasks, including classification, detection, segmentation, grounding, etc, using a single model without any task-specific heads. Combining these innovations on data and modeling, we present RemoteSAM, a foundation model that establishes new SoTA on several earth observation perception benchmarks, outperforming other foundation models such as Falcon, GeoChat, and LHRS-Bot with significantly higher efficiency.

draft: false
featured: true
tags:
  - Remote Sensing
  - Visual Foundation Model

image:
  filename: featured.jpg
  focal_point: Smart
  preview_only: false
  caption: The overview of RemoteSAM
  alt_text: RemoteSAM Architecture


date: 2025-07-05T00:00:00.000Z

---