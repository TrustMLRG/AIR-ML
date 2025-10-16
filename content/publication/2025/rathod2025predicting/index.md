---
title: "Predicting Time-varying Flux and Balance in Metabolic Systems using Structured Neural ODE Processes"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Santanu Rathod
- Pietro Liò
- Xiao Zhang

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2025-04-28T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2022-04-25T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ICLR 2025 Workshop on Machine Learning for Genomics Explorations 
publication_short: ICLR 2025 MLGenX Workshop

abstract: We develop a novel data-driven framework as an alternative to dynamic flux balance analysis, bypassing the demand for deep domain knowledge and manual efforts to formulate the optimization problem. The proposed framework is end-to-end, which trains a structured neural ODE process (SNODEP) model to estimate flux and balance samples using gene-expression time-series data. SNODEP is designed to circumvent the limitations of the standard neural ODE process model, including restricting the latent and decoder sampling distributions to be normal and lacking structure between context points for calculating the latent, thus more suitable for modeling the underlying dynamics of a metabolic system. Through comprehensive experiments (156 in total), we demonstrate that SNODEP not only predicts the unseen time points of real-world gene-expression data and the flux and balance estimates well but can even generalize to more challenging unseen knockout configurations and irregular data sampling scenarios, all essential for metabolic pathway analysis. We hope our work can serve as a catalyst for building more scalable and powerful models for genome-scale metabolic analysis.


# Summary. An optional shortened abstract.
summary: We propose a structured neural ODE process model to estimate flux and balance samples using gene-expression time-series data

tags: 
- Genome-Scale Metabolic Models 
- Neural Ordinary Differential Equation (ODE)
- Dynamic Flux and Balance Analysis (FBA)

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:

- name: ArXiv
  url: 'https://arxiv.org/abs/2410.14426'
  
- name: OpenReview
  url: 'https://openreview.net/forum?id=hs1AWLx6U5'

url_pdf: 'https://arxiv.org/pdf/2410.14426'
# url_code: 'https://github.com/XHMY/AutoDefense'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: 'https://vimeo.com/240662546'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  # caption: 'Convergence curves of the estimated best possible adversarial risk'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- rathod2025predicting

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->

