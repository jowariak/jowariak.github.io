---
title: 'Adapting Actively on the Fly: Relevance-Guided Online Meta-Learning with Latent Concepts for Geospatial Discovery'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Anindya Sarkar
- Yevgeniy Vorobeychik
- Elizabeth Bondi-Kelly

# Author notes (optional)
#author_notes:
 # - 'Equal contribution'
  #- 'Equal contribution'

date: '2026-09-24T00:00:00Z'

# Schedule page publish date (NOT publication's date).
#publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Neural Information Processing Systems 2026*
publication_short: In *NeurIPS 2026*

abstract: In environmental monitoring, data collection is often costly, sparse, and shaped by urgent public-health needs. This is particularly true for cancer-causing PFAS (Per- and polyfluoroalkyl substances) contamination, where discussions with domain experts and environmental organizations highlight the need to strategically identify high-risk, under-observed regions under tight sampling budgets. More broadly, similar challenges arise in disaster response and public health settings, where dynamic environments make it essential to efficiently uncover hidden targets from limited ground truth. Yet sparse and biased geospatial labels limit the applicability of existing learning-based methods, such as reinforcement learning. To address this, we propose a unified geospatial discovery framework that integrates active learning, online meta-learning, and concept-guided reasoning. Our approach introduces two key innovations built on a shared notion of concept relevance, capturing how domain-specific factors influence target presence: a concept-weighted uncertainty sampling strategy, where uncertainty is modulated by learned relevance from readily available concepts such as land cover and source proximity; and a relevance-aware meta-batch formation strategy that promotes semantic diversity during online-meta updates, improving generalization in dynamic environments. We evaluate our framework on PFAS contamination discovery as a real-world inspired environmental monitoring task, demonstrating robust target discovery under limited data and changing conditions.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Active learning
- Online meta learning
- Geospatial AI
- Relevance guided learning
- Concept based reasoning
- Data scarce learning
- Environmental monitoring
- PFAS contamination detection
- Budget constrained sampling
- Interpretable machine learning

# Display this page in the Featured widget?
featured: True

# Standard identifiers for auto-linking
# hugoblox:
 # ids:
    #doi: 10.3390/s23156729

# Custom links
links:
  - type: pdf
    url: https://arxiv.org/abs/2602.17605
 # - type: code
  #  url: https://github.com/HugoBlox/hugo-blox-builder
 # - type: dataset
  #  url: https://github.com/HugoBlox/hugo-blox-builder
 # - type: slides
  #  url: https://www.slideshare.net/
 # - type: source
  #  url: https://github.com/HugoBlox/hugo-blox-builder
  #- type: video
  #  url: https://youtube.com

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
 # - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: ""
---









