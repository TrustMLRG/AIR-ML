---
title: "SplineFlow: Flow Matching for Dynamical Systems with B-Spline Interpolants"

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

date: "2026-02-02T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2022-04-25T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ArXiv
# publication_short:

abstract: Flow matching is a scalable generative framework for characterizing continuous normalizing flows with wide-range applications. However, current state-of-the-art methods are not well-suited for modeling dynamical systems, as they construct conditional paths using linear interpolants that may not capture the underlying state evolution, especially when learning higher-order dynamics from irregular sampled observations. Constructing unified paths that satisfy multi-marginal constraints across observations is challenging, since naïve higher-order polynomials tend to be unstable and oscillatory. We introduce SplineFlow, a theoretically grounded flow matching algorithm that jointly models conditional paths across observations via B-spline interpolation. Specifically, SplineFlow exploits the smoothness and stability of B-spline bases to learn the complex underlying dynamics in a structured manner while ensuring the multi-marginal requirements are met. Comprehensive experiments across various deterministic and stochastic dynamical systems of varying complexity, as well as on cellular trajectory inference tasks, demonstrate the strong improvement of SplineFlow over existing baselines.

# Summary. An optional shortened abstract.
summary: We introduce SplineFlow, a B-spline based flow matching algorithm for modeling complex dynamical systems.

tags: 
- Flow Matching
- Modeling Dynamical Systems
- SDE & ODE
- B-Spline Interpolation

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:

- name: ArXiv
  url: 'https://arxiv.org/abs/2601.23072'
  
# - name: OpenReview
#   url: 'https://openreview.net/forum?id=hs1AWLx6U5'

url_pdf: 'https://arxiv.org/pdf/2601.23072'
url_code: 'https://github.com/santanurathod/SplineFlow'
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
- rathod2026splineflow

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

