---
title: 'Prototypical Fine-tuning: Towards Robust Performance Under Varying Data Sizes'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Xiting Wang
  - Yaru Hao
  - Yizhou Sun
  - Xing Xie

# Author notes (optional)
author_notes:
  - 'UCLA'
  - 'Microsoft Research Asia'
  - 'Microsoft Research Asia'
  - 'UCLA'
  - 'Microsoft Research Asia'

date: '2022-05-20 T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-05-20T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: Under Review # In *Proceedings of the 28th ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD'22)*
publication_short: Under Review 

abstract: In this paper, we move towards combining large parametric models with non-parametric prototypical networks. We propose prototypical fine-tuning, a novel prototypical framework for fine-tuning pretrained language models (LM), which automatically learns a bias to improve predictive performance for varying data sizes, especially low-resource settings. Our prototypical fine-tuning approach can automatically adjust the model capacity according to the data complexity and the model's inherent attributes. Moreover, we propose four principles for effective prototype fine-tuning towards the global optimum. Experimental results across various datasets show that our work achieves significant performance improvements under various low-resource settings, as well as comparable and usually better performances in high-resource scenarios. 

# Summary. An optional shortened abstract.
summary: Low-Resource, Natural Language Processing, Explainable AI,

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
  caption: 'Image credit: Yiqiao Jin'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - aaai2023

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
