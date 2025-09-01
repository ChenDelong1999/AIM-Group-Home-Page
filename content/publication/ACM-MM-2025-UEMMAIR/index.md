---
title: "UEMM-Air: Make Unmanned Aerial Vehicles Perform More Multi-modal Tasks"
publication_types:
  - "1" 
authors:
  - Liang Yao
  - Fan Liu
  - Shengxiang Xu
  - Chuanyi Zhang
  - Xing Ma
  - Jianyu Jiang
  - Zequan Wang
  - Shimin Di
  - Jun Zhou

publication: ACM International Conference on Multimedia
publication_short: "ACM MM 2025"

url_pdf: publication/ACM-MM-2025-UEMMAIR/UEMMAIR.pdf

abstract: The development of multi-modal learning for Unmanned Aerial Vehicles (UAVs) typically relies on a large amount of pixel-aligned multi-modal image data. However, existing datasets face challenges such as limited modalities, high construction costs, and imprecise annotations. To this end, we propose a synthetic multi-modal UAV-based multi-task dataset, UEMM-Air. Specifically, we simulate various UAV flight scenarios and object types using the Unreal Engine (UE). Then we design the UAV's flight logic to automatically collect data from different scenarios, perspectives, and altitudes. Furthermore, we propose a novel heuristic automatic annotation algorithm to generate accurate object detection labels. Finally, we utilize labels to generate text descriptions of images to make our UEMM-Air support more cross-modality tasks. In total, our UEMM-Air consists of 120k pairs of images with 6 modalities and precise annotations. Moreover, we conduct numerous experiments and establish new benchmark results on our dataset. We also found that models pre-trained on UEMM-Air exhibit better performance on downstream tasks compared to other similar datasets.

draft: false
featured: true
tags:
  - Unmanned Aerial Vehicles
  - Large Scale Dataset
  - Multi-modal
  - Multi-task

image:
  filename: featured.jpg
  focal_point: Smart
  preview_only: false
  caption: The Pipeline of data construction
  alt_text: The Pipeline of data construction


date: 2025-08-01T00:00:00.000Z

---