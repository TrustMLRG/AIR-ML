---
title: "Provably Cost-Sensitive Adversarial Defense via Randomized Smoothing"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Yuan Xin
- Dingfan Chen
- Michael Backes
- Xiao Zhang

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2025-06-06T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: Proceedings of the 42nd International Conference on Machine Learning
publication_short: ICML 2025
abstract: As ML models are increasingly deployed in crit- ical applications, robustness against adversarial perturbations is crucial. While numerous defenses have been proposed to counter such attacks, they typically assume that all adversarial transforma- tions are equally important, an assumption that rarely aligns with real-world applications. To ad- dress this, we study the problem of robust learn- ing against adversarial perturbations under cost- sensitive scenarios, where the potential harm of different types of misclassifications is encoded in a cost matrix. Our solution introduces a prov- ably robust learning algorithm to certify and opti- mize for cost-sensitive robustness, building on the scalable certification framework of randomized smoothing. Specifically, we formalize the defini- tion of cost-sensitive certified radius and propose our novel adaptation of the standard certification algorithm to generate tight robustness certificates tailored to any cost matrix. In addition, we design a robust training method that improves certified cost-sensitive robustness without compromising model accuracy. Extensive experiments on bench- mark datasets, including challenging ones unsolv- able by existing methods, demonstrate the effec- tiveness of our certification algorithm and training method across various cost-sensitive scenarios.

# Summary. An optional shortened abstract.
summary: We study how to certify and train for cost-sensitive robustness using randomized smoothing.

tags: 
- Certified Robustness
- Randomized Smoothing
- Cost-sensitive Learning


# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:

- name: ArXiv
  url: https://arxiv.org/abs/2310.08732
  
- name: OpenReview
  url: 'https://openreview.net/forum?id=D7qKAO34tp'

url_pdf: 'https://openreview.net/pdf?id=D7qKAO34tp'
url_code: 'https://github.com/AppleXY/Cost-Sensitive-RS'
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
- xin2025provably

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
The short version of this work was presented at workshops on [AdvML-Frontiers](https://advml-frontier.github.io/past/icml2023/index.html) at ICML 2023. The workshop paper can be found on [Openreview](https://openreview.net/pdf?id=6wDGBAs21z).

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
