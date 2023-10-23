---
title: Code Recommendation for Open Source Software Developers
summary: Code Recommendation for Open Source Software Developers.
tags:
  - Social Network Analysis
date: '2023-01-25T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: 'https://arxiv.org/abs/2210.08332'

image:
  caption: WebConf 2023 - CODER
  focal_point: Smart

links:
  - icon: twitter
    icon_pack: fab
    name: Follow
    url: https://twitter.com/AhrenJin
url_code: 'https://arxiv.org/abs/2210.08332'
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

Open Source Software (OSS) is forming the spines of technology infrastructures, attracting millions of talents to contribute. Notably, it is challenging and critical to consider both the developers' interests and the semantic features of the project code to recommend appropriate development tasks to OSS developers. In this paper, we formulate the novel problem of code recommendation, whose purpose is to predict the future contribution behaviors of developers given their interaction history, the semantic features of source code, and the hierarchical file structures of projects. We introduce CODER, a novel graph-based **CODE** **R**ecommendation framework for open source software developers, which accounts for the complex interactions among multiple parties within the system. CODER jointly models microscopic user-code interactions and macroscopic user-project interactions via a heterogeneous graph and further bridges the two levels of information through aggregation on file-structure graphs that reflect the project hierarchy. Moreover, to overcome the lack of reliable benchmarks, we construct three large-scale datasets to facilitate future research in this direction. Extensive experiments show that our CODER framework achieves superior performance under various experimental settings, including intra-project, cross-project, and cold-start recommendation. 
