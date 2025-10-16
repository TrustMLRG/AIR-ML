---
# Leave the homepage title empty to use the site title
title:
date: 2025-10-10
type: landing

sections:
  - block: hero
    content:
      title: |
         AIR-ML Lab @ CISPA
      images:
        # filename: welcome.jpg
        # caption: Group Retreat 2025 @ Buchnas Landhotel Saarschleife
        - filename: group_retreat_2025_treetop.jpg
          caption: Group Retreat at Treetop Saarschleife (Oct. 2025)
          date: "2025-09-29"
        - filename: group_retreat_2025_hotel.jpg
          caption: Group Retreat at Hotel Saarschleife (Oct. 2025)
          date: "2025-09-29"
        - filename: advik_oral_iclr_2025_BuildingTrust.jpg
          caption: Advik's Talk at ICLR BuildingTrust Workshop (Apr. 2025)
          date: "2025-04-28"
        # - filename: santanu_poster_iclr_2025_MLGenX.jpg
        #   caption: Santanu's Poster Presentation at ICLR MLGenX  (Apr. 2025)
        - filename: group_dinner_2024_osaka.jpg
          caption: Group Dinner at Osaka, Saabrücken (Dec. 2024)
          date: "2024-12-17"
      text: |
        <br>
        
        Led by [Dr. Xiao Zhang](https://xiao-zhang.net/), the AIR-ML lab conducts research on **A**dversarial, **I**nterpretable, and **R**obust **M**achine **L**earning (AIR-ML), with the ultimate goal of building trustworthy AI systems that are both resilient to attacks and transparent in their decision-making. Specifically, we analyze the dynamics of ML models, develop principled tools to audit and address their vulnerabilities, and build trustworthy AI systems for real-world applications. Our lab is currently affilated with [CISPA Helmholtz Center for Information Security](https://cispa.de/en) and located in Saarbrücken, Germany.
  
  - block: collection
    content:
      title: Latest News
      count: 10
      page_type: post
    design:
      view: list-news-clean
      columns: '1'

  # - block: collection
  #   content:
  #     title: Latest News
  #     subtitle:
  #     text:
  #     count: 5
  #     filters:
  #       author: ''
  #       category: ''
  #       exclude_featured: false
  #       publication_type: ''
  #       tag: ''
  #     offset: 0
  #     order: desc
  #     page_type: post
  #   design:
  #     view: list
  #     columns: '1'

  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen

  # - block: collection
  #   content:
  #     title: Latest Preprints
  #     text: ""
  #     count: 5
  #     filters:
  #       folders:
  #         - publication
  #       publication_type: 'article'
  #   design:
  #     view: citation
  #     columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./team/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
