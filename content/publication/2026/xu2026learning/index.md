---
title: "How Learning Dynamics Drive Adversarially Robust Generalization?"

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

date: "2026-06-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2022-04-25T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: 42nd Conference on Uncertainty in Artificial Intelligence
publication_short: UAI 2026

abstract: Despite being widely adopted as a canonical framework for learning robust models, adversarial training suffers from robust overfitting. Existing empirical measures and theoretical explorations are insufficient to provide satisfying mechanistic insights into the phenomenon. By viewing adversarial training with momentum SGD as a discrete-time dynamical system, we introduce a PAC-Bayesian analytical framework that proves time-resolved robust generalization bounds. Specifically, our framework tracks the closed-form evolution of the posterior mean and covariance under both stationary and non-stationary transient regimes, revealing their connections to the learning rate, the geometry of the loss landscape, and mini-batch stochastic gradients. By empirically approximating the statistical quantities implied by our theory, we offer a unified, mechanistic explanation for robust overfitting. We also illustrate why adversarial weight perturbation reduces the robust generalization gap by suppressing the loss curvature, but its design may be suboptimal for optimization due to over-penalization.

# Summary. An optional shortened abstract.
summary: We develop a time-resolved PAC-Bayesian framework that connects adversarially robust generalization to learning rate, loss lanscape curvature, and stochstic gradient variance, providing a mechanistic explanation for robust overfitting in adversarial training.

tags: 
- Adversarial Training
- Robust Overfitting
- Adversarial Robust Generalization
- PAC-Bayesian Analysis

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:

- name: ArXiv
  url: 'https://arxiv.org/abs/2410.07719'
  
# - name: OpenReview
#   url: 'https://openreview.net/forum?id=Vk8TCKhFNI'

url_pdf: 'https://openreview.net/pdf?id=Vk8TCKhFNI'
url_code: 'https://github.com/TrustMLRG/RobustGen'
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
- xu2026learning

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

