---
title: "Adapting Actively on the Fly: Relevance-Guided Online Meta-Learning with Latent Concepts for Geospatial Discovery"
authors:
- admin
- Anindya Sarkar
- Yevgeniy Vorobeychik


date: "2025-12-01T00:00:00Z"

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
#publication: ""
#publication_short: ""

abstract: |
  In many real-world settings, such as environmental monitoring, disaster response,
  or public health, where data is costly and difficult to collect, strategically
  sampling from unobserved regions is essential for uncovering hidden risks or
  targets under tight resource constraints. Moreover, real-world geospatial data
  is often sparse, noisy, and geographically skewed, rendering most existing
  learning-based methods impractical.

  To address this, we propose a unified geospatial discovery framework that
  integrates active learning, online meta-learning, and concept-guided reasoning
  to support efficient, real-time decision-making under extreme data scarcity.
  Our approach introduces two key innovations:

  (1) a relevance–uncertainty guided sampling strategy that uses structured
  relevance vectors based on domain-specific concepts (e.g., spectral channels,
  industrial proximity), enabling interpretable and adaptive sample selection; and

  (2) a relevance-aware meta-batch formation strategy that promotes semantic
  diversity during online meta-updates, improving generalization in dynamic
  environments.

  Our experiments include actively searching for a specific land cover type under
  sparse training conditions and a strict sampling budget, as well as identifying
  cancer-causing PFAS (per- and polyfluoroalkyl substances) contamination hotspots
  in U.S. surface water bodies, a critical real-world public health and environmental
  problem.

  Despite limited observations and significant landscape shifts, our method
  reliably uncovers target land covers and contamination zones and adapts across
  space and time, showcasing its scalability, robustness, and potential to
  accelerate discovery in data-limited, high-stakes environments.

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

featured: true

#hugoblox:
 # ids:
  #  arxiv: https://osf.io/preprints/osf/4wv8j_v1

links:
#- type: preprint
 # provider: arxiv
  #id: https://osf.io/preprints/osf/4wv8j_v1
#- type: code
#  url: https://github.com/HugoBlox/hugo-blox-builder
#- type: slides
 # url: https://www.slideshare.net/
#- type: dataset
 # url: "#"
#- type: poster
 # url: "#"
#- type: source
 # url: "#"
#- type: video
 # url: https://youtube.com
- type: custom
  label: Preprint (to be added soon)
  # url: https://openreview.net/forum?id=oZGsCCcq3H

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: ""
---



