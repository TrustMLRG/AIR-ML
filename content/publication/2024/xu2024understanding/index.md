---
title: "Understanding Adversarially Robust Generalization via Weight-Curvature Index"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Yuelin Xu
- Xiao Zhang

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2024-06-16T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2022-04-25T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['article']

# Publication name and optional abbreviated publication name.
publication: 2nd Workshop on High-dimensional Learning Dynamics (HiLD) at ICML 2024
publication_short: ICML 2024 HiLD Workshop

abstract: Despite numerous efforts, achieving adversarial robustness in deep learning remains a critical challenge. Recent studies have discovered that adversarial training, a widely adopted method for improving model robustness against adversarial perturbations, prevalently suffers from robust overfitting. To better characterize the robust generalization of adversarially trained models, we introduce the Weight-Curvature Index (WCI), a novel metric that captures the Frobenius norm of layer-wise weight matrices and the trace of the Hessian matrix with respect to the adversarial loss function. In particular, we establish a theoretical connection between WCI and robust generalization gap under a PAC-Bayesian framework. By analyzing the dynamics of these factors, WCI offers a nuanced understanding of why robust overfitting happens during adversarial training. Experimental results demonstrate a strong correlation between WCI and traditional robustness measures, suggesting the effectiveness of WCI in capturing the learning dynamics of adversarial training.


# Summary. An optional shortened abstract.
summary: We introduce the Weight-Curvature Index (WCI), a novel metric that captures the interplay between model parameters and loss landscape curvature to better understand and improve adversarially robust generalization in deep learning.

tags: 
- Adversarial Examples
- Adversarially Robust Generalization
- Weight-Curvature Index

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:

- name: ArXiv
  url: 'https://arxiv.org/abs/2410.07719'
  
- name: OpenReview
  url: 'https://openreview.net/forum?id=465Gv50E2N'

url_pdf: 'https://openreview.net/pdf?id=465Gv50E2N'
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
- xu2024understanding

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

