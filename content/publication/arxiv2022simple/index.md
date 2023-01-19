---
title: "A Simple Baseline for Adversarial Domain Adaptation-based Unsupervised Flood Forecasting"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- 陈德龙
- Ruizhi Zhou
- Yanling Pan
- 刘凡

# Author notes (optional)
# author_notes:

date: "2022-06-17T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-06-17T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: Technical Report. [[ArXiv]](https://arxiv.org/abs/2206.08105)
publication_short: Technical Report

abstract: 'Flood disasters cause enormous social and economic losses. However, both traditional physical models and learning-based flood forecasting models require massive historical flood data to train the model parameters. When come to some new site that does not have sufficient historical data, the model performance will drop dramatically due to overfitting. This technical report presents a Flood Domain Adaptation Network (FloodDAN), a baseline of applying Unsupervised Domain Adaptation (UDA) to the flood forecasting problem. Specifically, training of FloodDAN includes two stages: in the first stage, we train a rainfall encoder and a prediction head to learn general transferable hydrological knowledge on large-scale source domain data; in the second stage, we transfer the knowledge in the pretrained encoder into the rainfall encoder of target domain through adversarial domain alignment. During inference, we utilize the target domain rainfall encoder trained in the second stage and the prediction head trained in the first stage to get flood forecasting predictions. Experimental results on Tunxi and Changhua flood dataset show that FloodDAN can perform flood forecasting effectively with zero target domain supervision. The performance of the FloodDAN is on par with supervised models that uses 450-500 hours of supervision.'

# Summary. An optional shortened abstract.
summary: 'This technical report presents a Flood Domain Adaptation Network (FloodDAN), the first baseline of unsupervised flood forecasting problem.'
tags: [Deep Learning, Hydrological Forecasting]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:

url_pdf: 'publication/arxiv2022simple/A_Simple_Baseline_for_Adversarial_Domain_Adaptation_based_Unsupervised_Flood_Forecasting.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""

---

