---
title: 'Detecting Replay Attack on Voice-Controlled Systems using Small Neural Networks'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Nadeen Ahmed
  - admin
  - Nouran Sheta
  - Rahma Tarek
  - Imran Zualkernan
  - Fadi Aloul

# Author notes (optional)
#author_notes:
 # - 'Equal contribution'
  #- 'Equal contribution'

date: '2022-08-24T00:00:00Z'

# Schedule page publish date (NOT publication's date).
#publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *2022 IEEE 7th Forum on Research and Technologies for Society and Industry Innovation*
publication_short: In *IEEE RTSI*

abstract: Voice-control is becoming a common interface for many consumer IoT systems. Common threats to such systems include impersonation, replay, speech synthesis, and voice conversion attacks. Of these attacks, replay is the easiest to implement where a command is recorded and replayed. This paper explores the development of a lightweight intrusion detection neural network based on a recent command voice replay dataset. A lightweight model based on 1D Convolutional Neural Networks (CNN), and Long Short-Term Memory (LSTM) was proposed. The trained model was compared with baseline models based on Gaussian Mixture Models (GMM) using Constant Q Cepstral Coefficients (CQCC) and Mel-Frequency Cepstral Coefficient (MFCC). The proposed model outperformed the GMM models, and its size was significantly lower making it more feasible for embedded systems implementation.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
 - Voice-controlled systems
 - Voice security
 - Security / cyber-security
 - Replay attack detection
 - Spoofing detection
 - Speech processing / speech recognition
 - Neural networks / small neural networks
 - Machine learning for security
 - Audio forensics
 - Signal processing

# Display this page in the Featured widget?
featured: False

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.1109/RTSI55261.2022.9905158

# Custom links
links:
  - type: pdf
    url: https://ieeexplore.ieee.org/document/9905158
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

