---
title: "Safe in Isolation, Dangerous Together: Agent-Driven Multi-Turn Decomposition Jailbreaks on LLMs"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Devansh Srivastav
- Xiao Zhang

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2025-07-25T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2022-04-25T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: Proceedings of the 1st Workshop for Research on Agent Language Models (Oral)
publication_short: ACL 2025 REALM Workshop (Oral)

abstract: Large Language Models (LLMs) are increasingly deployed in critical domains, but their vulnerability to jailbreak attacks remains a significant concern. In this paper, we propose a multi-agent, multi-turn jailbreak strategy that systematically bypasses LLM safety mechanisms by decomposing harmful queries into seemingly benign sub-tasks. Built upon a role-based agentic framework consisting of a Question Decomposer, a Sub-Question Answerer, and an Answer Combiner, we demonstrate how LLMs can be manipulated to generate prohibited content without prompt manipulations. Our results show a drastic increase in attack success, often exceeding 90% across various LLMs, including GPT-3.5-Turbo, Gemma-2-9B, and Mistral-7B. We further analyze attack consistency across multiple runs and vulnerability across content categories. Compared to existing widely used jailbreak techniques, our multi-agent method consistently achieves the highest attack success rate across all evaluated models. These findings reveal a critical flaw in the current safety architecture of multi-agent LLM systems - their lack of holistic context awareness. By revealing this weakness, we argue for an urgent need to develop multi-turn, context-aware, and robust defenses to address this emerging threat vector.


# Summary. An optional shortened abstract.
summary: We propose a multi-agent, multi-turn jailbreak strategy that systematically bypasses LLM safety mechanisms by decomposing harmful queries into seemingly benign sub-tasks.

tags: 
- Large Language Models (LLMs)
- LLM Jailbreaks
- Multi-Agent Attack

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:

# - name: ArXiv
#   url: 'https://arxiv.org/abs/2410.14426'
  
# - name: OpenReview
#   url: 'https://openreview.net/forum?id=hs1AWLx6U5'

url_pdf: 'https://aclanthology.org/2025.realm-1.13.pdf'
# url_code: 'https://github.com/XHMY/AutoDefense'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
url_source: 'https://realm-workshop.github.io/accepted_papers/'
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
- srivastav2025safe

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

