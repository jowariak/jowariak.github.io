---
title: 'FOCUS on Contamination: Hydrology-Informed Noise-Aware Learning for Geospatial PFAS Mapping'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Alexa Friedman
- Sydney Evans
- Rachel Klein
- Runzi Wang
- Katherine E. Manz
- Kaley Beins
- David Q. Andrews
- Elizabeth Bondi-Kelly

# Author notes (optional)
#author_notes:
 # - 'Equal contribution'
  #- 'Equal contribution'

date: '2026-03-01T00:00:00Z'

# Schedule page publish date (NOT publication's date).
#publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *ICLR ML4RS Workshop*
publication_short: In *ICLR ML4RS*

abstract: Per- and polyfluoroalkyl substances (PFAS) are persistent environmental contaminants with significant public-health impacts, yet large-scale monitoring remains severely limited due to the high cost and logistical challenges of field sampling, and the difficulty of simulating their spread. As a result, scientific understanding of PFAS transport in surface waters is incomplete. At the same time, rich geospatial and satellite-derived data describing land cover, hydrology, and industrial activity are widely available, creating an opportunity for AI to integrate sparse observations with large-scale environmental context. We introduce FOCUS, a geospatial deep learning framework for PFAS contamination mapping that learns from sparse point measurements propagated over satellite-based raster data while explicitly accounting for the resulting label noise. Rather than assuming known governing equations, FOCUS incorporates priors derived from hydrological connectivity, land cover, source proximity, and sampling distance to model uncertainty in supervision. These priors are integrated into a principled noise-aware loss, yielding a robust training objective under label noise. Across extensive ablations, robustness analyses, and real-world validation, FOCUS consistently outperforms baselines including sparse segmentation, Kriging, and pollutant transport simulations, while preserving spatial coherence and scalability over large regions. Our results demonstrate how AI can support environmental science by combining large-scale geospatial data with sparse, uncertain measurements to enable reliable PFAS contamination screening in the absence of complete physical models.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Geospatial machine learning

- Environmental contamination mapping

- Noise-aware learning

- Weakly supervised segmentation

- Structured label noise

- Physics-guided machine learning

- Hydrology-informed modeling

- PFAS contamination

- Environmental health monitoring

- Uncertainty-aware prediction

# Display this page in the Featured widget?
featured: True

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.3390/s23156729

# Custom links
links:
  - type: pdf
    url: https://arxiv.org/abs/2502.14894
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
