---
title: "Generative Adversarial Suffix Prompter (GASP)"

subtitle: "GASP: Efficient Black-Box Generation of Adversarial Suffixes for Jailbreaking LLMs (NeurIPS 2025)" 

# event: Wowchemy Conference
# event_url: https://example.org

# location: Wowchemy HQ
# address:
#   street: 450 Serra Mall
#   city: Stanford
#   region: CA
#   postcode: '94305'
#   country: United States

summary: In our NeurIPS'25 paper, we develop Generative Adversarial Suffix Prompter (GASP),a novel black-box attack framework that leverages latent Bayesian optimization to generate human-readable adversarial suffixes.

# abstract: LLMs have demonstrated remarkable capabilities but remain highly susceptible to adversarial prompts despite extensive efforts for safety alignment, raising serious security concerns for their real-world adoptions. Existing jailbreak attacks rely on manual heuristics or computationally expensive optimization techniques, both struggling with generalization and efficiency. In this paper, we introduce GASP, a novel black-box attack framework that leverages latent Bayesian optimization to generate human-readable adversarial suffixes. Unlike prior methods, GASP efficiently explores continuous embedding spaces, optimizing for strong adversarial suffixes while preserving prompt coherence. We evaluate our method across multiple LLMs, showing its ability to produce natural and effective jailbreak prompts. Compared with alternatives, GASP significantly improves attack success rates and reduces computation costs, offering a scalable approach for red-teaming LLMs.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
# date: '2030-06-01T13:00:00Z'
# date_end: '2030-06-01T15:00:00Z'
# all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2025-09-18T00:00:00Z'

authors: [Advik Raj Basani, Xiao Zhang]
tags: [LLM, Adversarial ML, Jailbreak Attack]

# Is this a featured talk? (true/false)
featured: false

# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
#   focal_point: Right

links:
- name: OpenReview
  url: 'https://openreview.net/forum?id=0fBQAckQK3&referrer=%5B'

- name: AdvSuffixes Dataset
  url: 'https://github.com/TrustMLRG/GASP/tree/main/data/advsuffixes'

url_code: 'https://github.com/TrustMLRG/GASP'
url_pdf: 'https://openreview.net/pdf?id=0fBQAckQK3'
url_slides: ''
url_video: ''

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides:

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
---

<!-- Slides can be added in a few ways:

- **Create** slides using Wowchemy's [_Slides_](https://docs.hugoblox.com/managing-content/#create-slides) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://docs.hugoblox.com/writing-markdown-latex/).

Further event details, including page elements such as image galleries, can be added to the body of this page. -->

<!-- ### GASP: Efficient Black-Box Generation of Adversarial Suffixes for Jailbreaking LLMs (NeurIPS'25)

---- -->

### Abstract 

LLMs have demonstrated impressive capabilities across various natural language processing tasks yet remain vulnerable to prompts, known as jailbreak attacks, carefully designed to bypass safety guardrails and elicit harmful responses. Traditional methods rely on manual heuristics that suffer from limited generalizability. Despite being automatic, optimization-based attacks often produce unnatural jailbreak prompts that can be easily detected by safety filters or require high computational costs due to discrete token optimization. This paper introduces Generative Adversarial Suffix Prompter (GASP), a novel automated framework that can efficiently generate human-readable jailbreak prompts in a fully black-box setting. In particular, GASP leverages latent Bayesian optimization to craft adversarial suffixes by efficiently exploring continuous latent spaces, gradually optimizing the suffix generator to improve attack efficacy while balancing prompt coherence via a targeted iterative refinement procedure. Through comprehensive experiments, we show that GASP can produce natural adversarial prompts, significantly improving jailbreak success, reducing training times, and accelerating inference speed, thus making it an efficient and scalable solution for red-teaming LLMs.


<iframe
  src="https://gasp-llm.vercel.app/#demo"
  style="width:100%; height:1100px; border:none; overflow:hidden;"
  loading="lazy"
  scrolling="no"
></iframe>


### Ethical Statement

Our research is driven by the commitment to advancing the understanding of LLM vulnerabilities. While GASP enables the efficient generation of coherent adversarial suffixes, it is worth noting that manual methods for jailbreaking LLMs have already been widely accessible. Our research seeks to formalize and characterize these vulnerabilities rather than introduce novel threats. In alignment with responsible disclosure practices, we have shared our findings with relevant organizations whose models were tested in this study and transparently disclosed all of our findings.
