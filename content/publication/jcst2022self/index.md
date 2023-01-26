---
title: "Self-Supervised Music Motion Synchronization Learning for Music-Driven Conducting Motion Generation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Fan Liu
- Delong Chen
- Ruizhi Zhou
- Sai Yang
- Feng Xu

# Author notes (optional)
# author_notes:

date: "2022-03-10T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-03-10T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In [*Journal of Computer Science and Technology*](https://www.springer.com/journal/11390), 2022. [[doi]](https://doi.org/10.1007/s11390-022-2030-z)
publication_short: In *Journal of Computer Science and Technology*

abstract: 'The correlation between music and human motion has attracted widespread research attention. Although recent studies have successfully generated motion for singers, dancers, and musicians, few have explored motion generation for orchestral conductors. The generation of music-driven conducting motion should consider not only the basic music beats, but also mid-level music structures, high-level music semantic expressions, and hints for different parts of orchestras (strings, woodwind, etc.). However, most existing conducting motion generation methods rely heavily on human-designed rules, which significantly limits the quality of generated motion. Therefore, we propose a novel Music Motion Synchronized Generative Adversarial Network (M2S-GAN), which generates motions according to the automatically learned music representations. More specifically, M2S-GAN is a cross-modal generative network comprising four components: 1) a music encoder that encodes the music signal; 2) a generator that generates conducting motion from the music codes; 3) a motion encoder that encodes the motion; 4) a discriminator that differentiates the real and generated motions. These four components respectively imitate four key aspects of human conductors: understanding music, interpreting music, precision and elegance. The music and motion encoders are first jointly trained by a self-supervised contrastive loss, and can thus help to facilitate the music motion synchronization during the following adversarial learning process. To verify the effectiveness of our method we construct a large-scale dataset, named ConductorMotion100, which consists of an unprecedented 100 hours of conducting motion data. Extensive experiments on ConductorMotion100 demonstrate the effectiveness of M2S-GAN. Our proposed approach outperforms various comparison methods both quantitatively and qualitatively. Through visualization, we show that our approach can generate plausible, diverse, and music-synchronized conducting motion. To facilitate future research, both the dataset and experimental codes are open-sourced.'

# Summary. An optional shortened abstract.
summary: 'This paper proposed the  <font color=red>First</font> deep-learning based music-driven conducting motion generation method, and presented a large-scale music motion dataset ConductorMotion100 with unprecedented 100 hours length.'
tags: [Music Information Retrieval, Self-supervised Learning, Deep Learning, Multimodal Learning]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:

url_pdf: ''
url_code: 'https://github.com/ChenDelong1999/VirtualConductor'
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
- 音乐驱动的乐队指挥动作生成

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""

---

{{% callout note %}}
A competition is hold with the ConductorMotion100 dataset proposed in this paper. See [[here]](https://github.com/ChenDelong1999/VirtualConductor) for more details
{{% /callout %}}
