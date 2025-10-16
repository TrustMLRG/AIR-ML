---
title: "DivTrackee versus DynTracker: Promoting Diversity in Anti-Facial Recognition against Dynamic FR Strategy"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Wenshu Fan
- Minxing Zhang
- Hongwei Li
- Wenbo Jiang
- Hanxiao Chen
- Xiangyu Yue
- Michael Backes
- Xiao Zhang

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2025-01-11T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: The ACM Conference on Computer and Communications Security
publication_short: CCS 2025

abstract: The widespread adoption of facial recognition (FR) models raises serious concerns about their potential misuse, motivating the development of anti-facial recognition (AFR) to protect user facial privacy. In this paper, we argue that the static FR strategy, predominantly adopted in prior literature for evaluating AFR efficacy, cannot faithfully characterize the actual capabilities of determined trackers who aim to track a specific target identity. In particular, we introduce DynTracker, a dynamic FR strategy where the model's gallery database is iteratively updated with newly recognized target identity images. Surprisingly, such a simple approach renders all the existing AFR protections ineffective. To mitigate the privacy threats posed by DynTracker, we advocate for explicitly promoting diversity in the AFR-protected images. We hypothesize that the lack of diversity is the primary cause of the failure of existing AFR methods. Specifically, we develop DivTrackee, a novel method for crafting diverse AFR protections that builds upon a text-guided image generation framework and diversity-promoting adversarial losses. Through comprehensive experiments on various facial image benchmarks and feature extractors, we demonstrate DynTracker's strength in breaking existing AFR methods and the superiority of DivTrackee in preventing user facial images from being identified by dynamic FR strategies. We believe our work can act as an important initial step towards developing more effective AFR methods for protecting user facial privacy against determined trackers.

# Summary. An optional shortened abstract.
summary: We highlight the importance of using dynamic FR strategies to evaluate AFR methods, and propose DivTrackee as a promising countermeasure.

tags: 
- Anti-Facial Recognition
- Dynamic Facial Recognition Strategy
- Diversity-Promoting Adversarial Loss
- Text-Guided Generative Models

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: ArXiv
  url: 'https://arxiv.org/abs/2501.06533'
  
# - name: Link
#   url: 'http://proceedings.mlr.press/v70/wang17n'

url_pdf: 'https://arxiv.org/pdf/2501.06533'
url_code: 'https://github.com/fiora6/divtrackee'
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
- fan2025divtrackee

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
