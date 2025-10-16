---
title: "Stealthy Targeted Backdoor Attacks against Image Captioning"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Wenshu Fan
- Hongwei Li
- Wenbo Jiang
- Meng Hao
- Shui Yu
- Xiao Zhang

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2024-05-16T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2022-04-25T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: IEEE Transactions on Information Forensics and Security
publication_short: TIFS 2024

abstract: In recent years, there is an explosive growth in multimodal learning. Image captioning, a classical multimodal task, has demonstrated promising applications and attracted extensive research attention. However, recent studies have shown that image caption models are vulnerable to some security threats such as backdoor attacks. Existing backdoor attacks against image captioning typically pair a trigger either with a predefined sentence or a single word as the targeted output, yet they are unrelated to the image content, making them easily noticeable as anomalies by humans. In this paper, we present a novel method to craft targeted backdoor attacks against image caption models, which are designed to be stealthier than prior attacks. Specifically, our method first learns a special trigger by leveraging universal perturbation techniques for object detection, then places the learned trigger in the center of some specific source object and modifies the corresponding object name in the output caption to a predefined target name. During the prediction phase, the caption produced by the backdoored model for input images with the trigger can accurately convey the semantic information of the rest of the whole image, while incorrectly recognizing the source object as the predefined target. Extensive experiments demonstrate that our approach can achieve a high attack success rate while having a negligible impact on model clean performance. In addition, we show our method is stealthy in that the produced backdoor samples are indistinguishable from clean samples in both image and text domains, which can successfully bypass existing backdoor defenses, highlighting the need for better defensive mechanisms against such stealthy backdoor attacks.

# Summary. An optional shortened abstract.
summary: We present a novel method to craft targeted backdoor attacks against image caption models

tags: 
- Image Captioning
- Targeted Backdoor Attack
- Universal Adversarial Examples

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:

- name: Link
  url: 'https://ieeexplore.ieee.org/abstract/document/10531257'

- name: ArXiv
  url: 'https://arxiv.org/abs/2406.05874'
  
# - name: OpenReview
#   url: 'https://openreview.net/forum?id=6ET9SzlgNX&noteId=3E3haWzrQPr'

url_pdf: 'https://arxiv.org/pdf/2406.05874'
# url_code: 'https://github.com/TrustMLRG/EDAC'
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
- fan2024stealthy

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

