---
title: "FEVA-ICS: Benchmarking Adversarial Robustness of Machine Learning-based Intrusion Detection Systems in Industrial Control Systems"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Madhurima Ghosh
- Ankush Meshram
- Markus Karch
- Christian Haas
- Xiao Zhang
- Mridula Singh

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2026-03-16T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2022-04-25T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication:  Proceedings of the 12th ACM Cyber-Physical System Security Workshop
publication_short: CPSS 2026

abstract: Machine Learning (ML)-based Intrusion Detection Systems (IDS) are increasingly proposed for deployment in Industrial Control Systems (ICS) to detect evolving and previously unseen attacks. However, ML models are vulnerable to adversarial examples, i.e., carefully crafted inputs that induce misclassification while remaining functionally valid and physically plausible. In safety-critical ICS environments, this vulnerability makes systematic robustness benchmarking essential prior to deployment. In this paper, we introduce the Framework for Evasion and Validation for Industrial Control Systems (FEVA-ICS), a novel end-to-end benchmarking platform designed to assess ML-based IDS robustness in a realistic black-box setting. FEVA-ICS incorporates two attack strategies, a query-based approach and a surrogate model-based approach. In particular, we propose Correlation-Driven Feature Shift (CorrShift), a novel query-based adversarial attack tailored for ICS that preserves physical plausibility and temporal consistency. We also include surrogate-model transfer attacks using gradient-based methods, such as Fast Gradient Sign Method (FGSM) and Projected Gradient Descent (PGD). Through comprehensive experiments, we show that CorrShift consistently outperforms surrogate-based attacks in effectiveness and generalizability, highlighting the importance of ICS-aware adversarial design. The results underscore the need for adversarial robustness evaluation in ML-based IDS pipelines. FEVA-ICS establishes a practical and extensible benchmark for adversarial robustness assessment, supporting safer and more reliable deployment of ML-based IDS in real-world ICS environments.

# Summary. An optional shortened abstract.
summary: we introduce FEVA-ICS, a novel end-to-end benchmarking platform designed to assess ML-based IDS robustness in a realistic black-box setting

tags: 
- Adversarial Examples
- Industrial Control System (ICS)
- ML-based Intrusion Detection System (IDS)

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:

# - name: ArXiv
#   url: 'https://arxiv.org/abs/2410.07719'
  
# - name: OpenReview
#   url: 'https://openreview.net/forum?id=Vk8TCKhFNI'

url_pdf: 'https://dl.acm.org/doi/epdf/10.1145/3775042.3807884'
# url_code: 'https://github.com/TrustMLRG/RobustGen'
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
- ghosh2026feva

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

