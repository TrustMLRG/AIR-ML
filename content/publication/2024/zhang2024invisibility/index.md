---
title: "Invisibility Cloak: Disappearance under Human Pose Estimation via Backdoor Attacks"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Minxing Zhang
- Michael Backes
- Xiao Zhang

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2024-10-10T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2022-04-25T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['article']

# Publication name and optional abbreviated publication name.
publication: ArXiv
# publication_short: arxiv

abstract: Human Pose Estimation (HPE) has been widely applied in autonomous systems such as self-driving cars. However, the potential risks of HPE to adversarial attacks have not received comparable attention with image classification or segmentation tasks. Existing works on HPE robustness focus on misleading an HPE system to provide wrong predictions that still indicate some human poses. In this paper, we study the vulnerability of HPE systems to disappearance attacks, where the attacker aims to subtly alter the HPE training process via backdoor techniques so that any input image with some specific trigger will not be recognized as involving any human pose. As humans are typically at the center of HPE systems, such attacks can induce severe security hazards, e.g., pedestrians' lives will be threatened if a self-driving car incorrectly understands the front scene due to disappearance attacks. To achieve the adversarial goal of disappearance, we propose IntC, a general framework to craft Invisibility Cloak in the HPE domain. The core of our work lies in the design of target HPE labels that do not represent any human pose. In particular, we propose three specific backdoor attacks based on our IntC framework with different label designs. IntC-S and IntC-E, respectively designed for regression- and heatmap-based HPE techniques, concentrate the keypoints of triggered images in a tiny, imperceptible region. Further, to improve the attack's stealthiness, IntC-L designs the target poisons to capture the label outputs of typical landscape images without a human involved, achieving disappearance and reducing detectability simultaneously. Extensive experiments demonstrate the effectiveness and generalizability of our IntC methods in achieving the disappearance goal. By revealing the vulnerability of HPE to disappearance and backdoor attacks, we hope our work can raise awareness of the potential risks when HPE models are deployed in real-world applications.

# Summary. An optional shortened abstract.
summary: We propose a general framework to craft invisibility cloak for human pose estimation models

tags: 
- Backdoor attack
- Invisibility Cloak
- Human Pose Estimation

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:

- name: ArXiv
  url: 'https://arxiv.org/abs/2410.07670'
  
# - name: OpenReview
#   url: 'https://openreview.net/forum?id=6ET9SzlgNX&noteId=3E3haWzrQPr'

url_pdf: 'https://arxiv.org/pdf/2410.07670'
# url_code: ''
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
- zhang2024invisibility

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

