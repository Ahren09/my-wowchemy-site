---
title: 'Reinforcement Subgraph Reasoning for Fake News Detection'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Changyu Chen
  - Xiting Wang
  - admin
  - Victor Ye Dong
  - Li Dong
  - Jie Cao
  - Yi Liu
  - Rui Yan
# Author notes (optional)
author_notes:
  - 'Renmin University of China'
  - 'Microsoft Research Asia'
  - 'Georgia Institute of Technology'
  - 'Microsoft Research Redmond'
  - 'Microsoft Research Asia'
  - 'Microsoft Research Redmond'
  - 'Microsoft Research Redmond'
  - 'Renmin University of China'

date: '2022-05-01 T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-05-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 28th ACM SIGKDD Conference on Knowledge Discovery and Data Mining (ICML'23)*
publication_short: In ICML2023

abstract: In reinforcement learning (RL), there are two major settings for interacting with the environment --- online and offline. Online methods explore the environment at significant time cost, and offline methods efficiently obtain reward signals by sacrificing exploration capability.   We propose semi-offline RL, a novel paradigm that smoothly transits from offline to online settings, balances exploration capability and training cost, and provides a theoretical foundation for comparing different RL settings. Based on the semi-offline formulation, we present the RL setting that is optimal in terms of optimization cost, asymptotic error, and overfitting error bound. Extensive experiments show that our semi-offline approach is efficient and yields comparable or often better performance compared with state-of-the-art methods. Our code is available on <a href="https://github.com/ChangyuChen347/semi-offline-RL">GitHub</a>

# Summary. An optional shortened abstract.
summary: Reinforcement Learning, Natural Language Processing

tags: [Reinforcement Learning, Natural Language Processing]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2306.09712'
url_code: 'https://github.com/ChangyuChen347/semi-offline-RL'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - icml2023

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
