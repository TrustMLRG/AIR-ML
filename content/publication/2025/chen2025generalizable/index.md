---
title: "Generalizable Targeted Data Poisoning against Varying Physical Objects"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Zhizhen Chen
- Zhengyu Zhao
- Subrat Kishore Dutta
- Chenhao Lin
- Chao Shen
- Xiao Zhang

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2025-07-26T00:00:00Z"
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
# publication_short: arxiv

abstract: Targeted data poisoning (TDP) aims to compromise the model's prediction on a specific (test) target by perturbing a small subset of training data. Existing work on TDP has focused on an overly ideal threat model in which the same image sample of the target is used during both poisoning and inference stages. However, in the real world, a target object often appears in complex variations due to changes of physical settings such as viewpoint, background, and lighting conditions. In this work, we take the first step toward understanding the real-world threats of TDP by studying its generalizability across varying physical conditions. In particular, we observe that solely optimizing gradient directions, as adopted by the best previous TDP method, achieves limited generalization. To address this limitation, we propose optimizing both the gradient direction and magnitude for more generalizable gradient matching, thereby leading to higher poisoning success rates. For instance, our method outperforms the state of the art by 19.49% when poisoning CIFAR-10 images targeting multi-view cars.

# Summary. An optional shortened abstract.
summary: We take the first step toward understanding the real-world threats of TDP by studying its generalizability across varying physical conditions.

tags: 
- Clean-Label Data Poisoning Attacks
- Supopulation Attacks
- Gradient Matching

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: ArXiv
  url: 'https://arxiv.org/abs/2412.03908'
  
# - name: Link
#   url: 'http://proceedings.mlr.press/v70/wang17n'

url_pdf: 'https://arxiv.org/pdf/2412.03908.pdf'
url_code: https://github.com/jiaangk/generalizable_tcpa
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
  focal_point: "Center"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- chen2025generalizable

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
