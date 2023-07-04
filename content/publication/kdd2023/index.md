---
title: 'Predicting Information Pathways Across Online Communities'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Yeon-Chang Lee
  - Kartik Sharma
  - Meng Ye
  - Karan Sikka
  - Ajay Divakaran
  - Srijan Kumar

# Author notes (optional)
author_notes:
  - 'Georgia Institute of Technology'
  - 'Georgia Institute of Technology'
  - 'Georgia Institute of Technology'
  - 'SRI International'
  - 'SRI International'
  - 'SRI International'
  - 'Georgia Institute of Technology'

date: '2023-05-18 T00:00:00Z'
doi: ''

# Note: the publishDate cannot be in the future
# Schedule page publish date (NOT publication's date).
publishDate: '2023-05-18 T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 29th ACM SIGKDD International Conference on Knowledge Discovery and Data Mining*
publication_short: In *KDD2023*

abstract: The problem of **community-level information pathway prediction** (CLIPP) aims at predicting the transmission trajectory of content across online communities. A successful solution to CLIPP holds significance as it facilitates the distribution of valuable information to a larger audience and prevents the proliferation of misinformation. Notably, solving CLIPP is non-trivial as inter-community relationships and influence are unknown, information spread is multi-modal, and new content and new communities appear over time. In this work, we address CLIPP by collecting large-scale, multi-modal datasets to examine the diffusion of online YouTube videos on Reddit. We analyze these datasets to construct community influence graphs (CIGs) and develop a novel dynamic graph framework, INPAC (Information Pathway Across Online Communities), which incorporates CIGs to capture the temporal variability and multi-modal nature of video propagation across communities. Experimental results in both warm-start and cold-start scenarios show that INPAC outperforms seven baselines in CLIPP. Our code and datasets are available <a href="https://github.com/claws-lab/INPAC">here</a>

# Summary. An optional shortened abstract.
summary: Modeling Information Pathways 

tags: [GNN, Recommender System, Social Network Analysis, Data Mining, Information Pathway]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2306.02259'
url_code: 'https://github.com/claws-lab/INPAC.git'
url_dataset: 'https://github.com/claws-lab/INPAC.git'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://youtu.be/xlWkXHa0gio'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Our Proposed INPAC Framework'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - kdd2023

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
