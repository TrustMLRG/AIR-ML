---
title: "Controllable Adversarial Makeup for Privacy via Text-Guided Diffusion"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Youngjin Kwon
- Xiao Zhang
# Author notes (optional)
# author_notes:
# - "Equal contribution"

date: "2025-07-27T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication:  ArXiv
# publication_short: ICLR 2025 FM-Wild Workshop

abstract: As face recognition becomes more widespread in government and commercial services, its potential misuse raises serious concerns about privacy and civil rights. To counteract this threat, various anti-facial recognition techniques have been proposed, which protect privacy by adversarially perturbing face images. Among these, generative makeup-based approaches are the most widely studied. However, these methods, designed primarily to impersonate specific target identities, can only achieve weak dodging success rates while increasing the risk of targeted abuse. In addition, they often introduce global visual artifacts or a lack of adaptability to accommodate diverse makeup prompts, compromising user satisfaction. To address the above limitations, we develop MASQUE, a novel diffusion-based framework that generates localized adversarial makeups guided by user-defined text prompts. Built upon precise null-text inversion, customized cross-attention fusion with masking, and a pairwise adversarial guidance mechanism using images of the same individual, MASQUE achieves robust dodging performance without requiring any external identity. Comprehensive evaluations on open-source facial recognition models and commercial APIs demonstrate that MASQUE significantly improves dodging success rates over all baselines, along with higher perceptual fidelity preservation, stronger adaptability to various makeup prompts, and robustness to image transformations.


# Summary. An optional shortened abstract.
summary: We introduce MASQUE, a diffusion-based framework that generates localized adversarial makeup guided by user-defined text prompts.

tags: 
- Anti-Facial Recognition
- Diffusion Models

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: ArXiv
  url: 'https://arxiv.org/abs/2503.10549'
  
# - name: OpenReview
#   url: 'https://openreview.net/forum?id=ydTE0tpZ90'

url_pdf: 'https://arxiv.org/pdf/2503.10549'
url_code: 'https://github.com/TrustMLRG/MASQUE'
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
- kwon2025masque

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
The short version of this work was presented at [FM-Wild Workshop](https://fm-wild-community.github.io/) at ICLR 2025. The workshop paper can be found on [Openreview](https://openreview.net/forum?id=ydTE0tpZ90).

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
