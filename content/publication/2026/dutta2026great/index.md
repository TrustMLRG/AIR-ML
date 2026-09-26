---
title: "GREAT: Generalizable Backdoor Attacks in RLHF via Emotion-Aware Trigger Synthesis"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Subrat Kishore Dutta
- Yuelin Xu
- Piyush Pant
- Xiao Zhang

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2026-08-28T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: The 2026 Conference on Empirical Methods in Natural Language Processing
publication_short: Findings of EMNLP 2026

abstract: Recent work has shown that RLHF is highly susceptible to backdoor attacks. However, existing methods often rely on rare tokens or fixed triggers, limiting their impact in realistic scenarios. In this work, we develop GREAT, a novel framework for crafting natural distributional backdoors in RLHF. Specifically, GREAT targets harmful response generation for a vulnerable user subpopulation featured by semantically violent requests paired with emotionally angry triggers. At the core of our framework is a trigger identification pipeline that operates in the model's latent embedding space, leveraging dimensionality reduction and clustering techniques to identify representative triggers. To enable this, we introduce a hierarchical and diversity-driven prompting strategy to construct Erinyes, a high-quality dataset of over 5,000 angry triggers curated from GPT-4.1. Our experiments show that GREAT significantly outperforms baselines in attack generalization to unseen triggers, while preserving standard utility and maintaining stealth under defenses.

# Summary. An optional shortened abstract.
summary: GREAT exposes a realistic RLHF vulnerability by targeting a semantic trigger distribution and using latent-space medoid selection to implant distributional backdoors that generalize to unseen triggers while preserving utility and evading defenses.

tags: 
- RLHF
- Subpopulation Data Poisoning
- Emotion-Aware Trigger Synthesis
- Generative AI

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: ArXiv
  url: 'https://arxiv.org/abs/2510.09260'
  
# - name: Link
#   url: 'http://proceedings.mlr.press/v70/wang17n'

url_pdf: 'https://arxiv.org/pdf/2510.09260'
url_code: 'https://github.com/PiyushWithPant/GREAT.git'
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
- dutta2026great

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
