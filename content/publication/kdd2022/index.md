---
title: 'Reinforcement Subgraph Reasoning for Fake News Detection'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Ruichao Yang
  - Xiting Wang
  - admin
  - Chaozhuo Li
  - Jianxun Lian
  - Xing Xie

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-05-18 T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-05-18T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 28th ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD'22)*
publication_short: In *AAAI*

abstract: The wide spread of fake news has caused serious societal issues. We propose a subgraph reasoning paradigm for fake news detection, which provides a crystal type of explainability by revealing which subgraphs of the news propagation network are the most important for news verification, and concurrently improves the generalization and discrimination power of graph-based detection models by removing task-irrelevant information. In particular, we propose a reinforced subgraph generation method, and perform fine-grained modeling on the generated subgraphs by developing a Hierarchical Path-aware Kernel Graph Attention Network. We also design a curriculum-based optimization method to \xiting{ensure better convergence} and train the two parts in an end-to-end manner. Extensive experiments show that our model outperforms the state-of-the-art methods and demonstrate the explainability of our method.

# Summary. An optional shortened abstract.
summary: Fake News Detection, Natural Language Processing, 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - aaai2022

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: AAAI22-FakeNews
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
