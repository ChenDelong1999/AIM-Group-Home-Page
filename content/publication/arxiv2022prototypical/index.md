---
title: Prototypical Contrastive Language Image Pretraining
abstract: "Contrastive Language Image Pretraining (CLIP) received widespread
  attention since its learned representations can be transferred well to various
  downstream tasks. During CLIP training, the InfoNCE objective aims to align
  positive image-text pairs and separate negative ones. In this paper, we show a
  representation grouping effect during this process: the InfoNCE objective
  indirectly groups semantically similar representations together via randomly
  emerged within-modal anchors. We introduce Prototypical Contrastive Language
  Image Pretraining (ProtoCLIP) to enhance such grouping by boosting its
  efficiency and increasing its robustness against modality gap. Specifically,
  ProtoCLIP sets up prototype-level discrimination between image and text
  spaces, which efficiently transfers higher-level structural knowledge. We
  further propose Prototypical Back Translation (PBT) to decouple representation
  grouping from representation alignment, resulting in effective learning of
  meaningful representations under large modality gap. PBT also enables us to
  introduce additional external teachers with richer prior knowledge. ProtoCLIP
  is trained with an online episodic training strategy, which makes it can be
  scaled up to unlimited amounts of data. Combining the above novel designs, we
  train our ProtoCLIP on Conceptual Captions and achieved an +5.81% ImageNet
  linear probing improvement and an +2.01% ImageNet zero-shot classification
  improvement."
slides: ""
url_pdf: publication/arxiv2022prototypical/prototypical_contrastive_language_image_pretraining.pdf
publication_types:
  - "3"
authors:
  - Delong Chen
  - Zhao Wu
  - Fan Liu
  - Zaiquan Yang
  - Yixiang Huang
  - Yiping Bao
  - Erjin Zhou
publication: Technical Report. [[ArXiv]](https://arxiv.org/abs/2206.10996)
featured: true
tags:
  - Deep Learning
  - Multimodal Learning
  - Computer Vision
  - Self-supervised Learning
projects:
  - 视觉-语言大规模多模态预训练
summary: "In this paper, we show a representation grouping effect during this
  process: the InfoNCE objective indirectly groups semantically similar
  representations together via randomly emerged within-modal anchors.  We
  introduce Prototypical Contrastive Language Image Pretraining (ProtoCLIP) to
  enhance such grouping by boosting its efficiency and increasing its robustness
  against modality gap."
url_dataset: ""
url_project: ""
publication_short: Technical Report
url_source: ""
url_video: ""
date: 2022-06-23T00:00:00Z
url_slides: ""
links: null
image:
  preview_only: false
publishDate: 2022-06-23T00:00:00Z
url_poster: ""
url_code: https://github.com/megvii-research/protoclip
doi: ""
---
