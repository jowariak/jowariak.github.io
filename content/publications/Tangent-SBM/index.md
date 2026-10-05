---
title: "Tangent Schrödinger Bridge Matching: Learning Stochastic Transport with Mechanistic Sensitivities"

authors:
  - admin
  - Elizabeth Bondi-Kelly

date: "2026-09-30T00:00:00Z"

publication_types:
  - paper-conference

publication: "In NeurIPS, AI for Stochastic Dynamics [Under review at ICLR 2027]"
publication_short: "In NeurIPS, AI for Stochastic Dynamics [Under review at ICLR 2027]"

abstract: >-
  Diffusion Schrödinger bridges learn stochastic transports between endpoint distributions while remaining close to a reference diffusion, enabling flexible modeling of stochastic transformations between observed states. However, a learned bridge can match observed endpoint distributions while responding incorrectly when a physical condition or parameter is perturbed. We introduce Tangent-SBM, which propagates intervention sensitivities alongside trajectories of the learned conditional SDE, allowing externally supplied sensitivity information to constrain how the learned stochastic dynamics respond when u changes. When a sensitivity target is defined for each stochastic realization, we match it directly. When only the conditional mean sensitivity is known, we use two independent stochastic trajectories to match that mean without explicitly penalizing legitimate variation across trajectories. Across an analytically controlled Gaussian system, a stochastic double well, and the official PDEBench two-dimensional diffusion--reaction simulator extended with parameter interventions, Tangent-SBM consistently reduces intervention-sensitivity error. On PDEBench, it reduces directional sensitivity error by 37--44% relative to Conditional DSBM while maintaining comparable terminal-field accuracy.

tags:
  - Schrödinger bridges
  - Stochastic dynamics
  - Generative modeling
  - Scientific machine learning
  - Sensitivity analysis
  - Intervention modeling
  - Diffusion models
  - PDEBench

featured: true

hugoblox:
  ids:
    doi: 10.48550/arXiv.2610.02906

links:
  - type: pdf
    url: "https://arxiv.org/abs/2610.02906"

#links:
 # - type: pdf
  #  url: "tangent-sbm.pdf"

image:
  focal_point: ""
  preview_only: false
---
