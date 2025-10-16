---
title: "Improving the Efficiency of Self-Supervised Adversarial Training through Latent Clustering-based Selection"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Somrita Ghosh
- Yuelin Xu
- Xiao Zhang

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2024-07-24T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2022-04-25T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: The Next Generation of AI Safety Workshop at ICML 2024
publication_short: ICML 2024 NextGenAISafety Workshop

abstract: Compared to standard learning, adversarially robust learning is widely recognized to require a much larger training dataset. Recent works utilize external or synthetically generated unlabeled data in adversarial training using self-supervised learning. Despite achieving enhanced robustness, these methods typically require a considerable amount of additional data, leading to substantial memory consumption and convergence time. To address the space and computational challenges, we propose a novel Latent Clustering-based Selection scheme (LCS) to strategically select a small core subset of unlabeled data critical for obtaining better robustness. In particular, our method prioritizes selecting unlabeled data that are close to the model's decision boundary, while balancing the ratio between the boundary and the remaining data points to avoid overfitting. Our experiments show that when incorporated into self-supervised adversarial training, our LCS scheme can significantly reduce the memory and time complexities while achieving comparable model robustness.


# Summary. An optional shortened abstract.
summary: We introduce a Latent Clustering-based Selection method to choose a core subset from the entire unlabeled dataset, aiming to improve the efficiency of self-supervised adversarial training while preserving robustness.

tags: 
- Adversarial Robustness
- Self-Supervised Learning
- Data Efficiency

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:

# - name: ArXiv
#   url: 'https://arxiv.org/abs/2403.04783'
  
- name: OpenReview
  url: 'https://openreview.net/forum?id=FjZsM7D9AT'

url_pdf: 'https://openreview.net/pdf?id=FjZsM7D9AT'
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
- ghosh2024improving

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

