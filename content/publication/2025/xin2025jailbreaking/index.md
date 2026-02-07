---
title: "Jailbreaking Attacks vs. Content Safety Filters: How Far Are We in the LLM Safety Arms Race?"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Yuan Xin
- Dingfan Chen
- Linyi Yang
- Michael Backes
- Xiao Zhang

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2025-12-30T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2022-04-25T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ArXiv
# publication_short:

abstract: As large language models (LLMs) are increasingly deployed, ensuring their safe use is paramount. Jailbreaking, adversarial prompts that bypass model alignment to trigger harmful outputs, present significant risks, with existing studies reporting high success rates in evading common LLMs. However, previous evaluations have focused solely on the models, neglecting the full deployment pipeline, which typically incorporates additional safety mechanisms like content moderation filters. To address this gap, we present the first systematic evaluation of jailbreak attacks targeting LLM safety alignment, assessing their success across the full inference pipeline, including both input and output filtering stages. Our findings yield two key insights - first, nearly all evaluated jailbreak techniques can be detected by at least one safety filter, suggesting that prior assessments may have overestimated the practical success of these attacks; second, while safety filters are effective in detection, there remains room to better balance recall and precision to further optimize protection and user experience. We highlight critical gaps and call for further refinement of detection accuracy and usability in LLM safety systems.

# Summary. An optional shortened abstract.
summary: We present the first systematic evaluation of jailbreak attacks targeting LLM safety alignment, assessing their success across the full inference pipeline, including both input and output filtering stages.

tags: 
- LLM Safety
- Jailbreak Attacks
- Content Safety Filters

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:

- name: ArXiv
  url: 'https://www.arxiv.org/abs/2512.24044'
  
# - name: OpenReview
#   url: 'https://openreview.net/forum?id=hs1AWLx6U5'

url_pdf: 'https://www.arxiv.org/pdf/2512.24044'
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
- xin2025jailbreaking

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

