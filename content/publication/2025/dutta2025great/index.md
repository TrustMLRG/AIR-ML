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

date: "2025-10-10T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ArXiv
# publication_short: ICCV 2025

abstract: Recent work has shown that RLHF is highly susceptible to backdoor attacks, poisoning schemes that inject malicious triggers in preference data. However, existing methods often rely on static, rare-token-based triggers, limiting their effectiveness in realistic scenarios. In this paper, we develop GREAT, a novel framework for crafting generalizable backdoors in RLHF through emotion-aware trigger synthesis. Specifically, GREAT targets harmful response generation for a vulnerable user subgroup characterized by both semantically violent requests and emotionally angry triggers. At the core of GREAT is a trigger identification pipeline that operates in the latent embedding space, leveraging principal component analysis and clustering techniques to identify the most representative triggers. To enable this, we present Erinyes, a high-quality dataset of over 5000 angry triggers curated from GPT-4.1 using a principled, hierarchical, and diversity-promoting approach. Experiments on benchmark RLHF datasets demonstrate that GREAT significantly outperforms baseline methods in attack success rates, especially for unseen trigger scenarios, while largely preserving the response quality on benign inputs.

# Summary. An optional shortened abstract.
summary: we develop a novel framework for crafting generalizable backdoors in RLHF through emotion-aware trigger synthesis

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
# url_code: 'https://github.com/subratkishoredutta/IAP'
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
- dutta2025great

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
