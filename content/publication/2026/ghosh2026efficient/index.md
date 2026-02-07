---
title: "Efficient Semi-Supervised Adversarial Training via Latent Clustering-Based Data Reduction"

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

date: "2026-01-30T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2022-04-25T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["Conference paper"]

# Publication name and optional abbreviated publication name.
publication: The 4th IEEE Conference on Secure and Trustworthy Machine Learning
publication_short: SaTML 2026

# publication: The Next Generation of AI Safety Workshop at ICML 2024
# publication_short: ICML 2024 NextGenAISafety Workshop

abstract: Learning robust models under adversarial settings is widely recognized as requiring a considerably large number of training samples. Recent work proposes semi-supervised adversarial training (SSAT), which utilizes external unlabeled or synthetically generated data and is currently the state of the art. However, SSAT requires substantial extra data to attain high robustness, resulting in prolonged training time and increased memory usage. In this paper, we propose data reduction strategies to improve the efficiency of SSAT by optimizing the amount of additional data incorporated. Specifically, we design novel latent clustering-based techniques to select or generate a small, critical subset of data samples near the model's decision boundary. While focusing on boundary-adjacent points, our methods maintain a balanced ratio between boundary and non-boundary data points, thereby avoiding overfitting. Comprehensive experiments across image benchmarks demonstrate that our methods can effectively reduce SSAT's data requirements and computational costs while preserving its strong robustness advantages. In particular, our latent-space selection scheme based on k-means clustering and our guided diffusion-based approach with LCG-KM are the most effective, achieving nearly identical robust accuracies with 5x to 10x less unlabeled data. When compared to full SSAT trained to convergence, our methods reduce total runtime by approximately 3x to 4x due to strategic prioritization of unlabeled data.


# Summary. An optional shortened abstract.
summary: We introduce latent clustering-based data reduction methods to choose a core subset from the entire unlabeled dataset, aiming to improve the efficiency of semi-supervised adversarial training while preserving robustness.

tags: 
- Adversarial Robustness
- Semi-Supervised Learning
- Data Efficiency

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:

- name: ArXiv
  url: 'https://arxiv.org/abs/2501.10466'
  
# - name: OpenReview
#   url: 'https://openreview.net/forum?id=FjZsM7D9AT'

url_pdf: 'https://arxiv.org/pdf/2501.10466'
url_code: 'https://github.com/TrustMLRG/EfficientSSAT'
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
- ghosh2026efficient

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

A preliminary version of this work was presented at [NextGenAISafety Workshop](https://icml-nextgenaisafety.github.io/) at ICML 2024. The workshop paper can be found on [Openreview](https://openreview.net/forum?id=FjZsM7D9AT).
