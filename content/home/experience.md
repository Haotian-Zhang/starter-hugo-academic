---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Research Intern, Deep Learning
    company: Microsoft Research
    company_url: 'https://www.microsoft.com/en-us/research/group/deep-learning-group/'
    company_logo: org-ms
    location: Redmond, USA
    date_start: '2021-06-22'
    date_end: '2021-09-17'
    description: |2-
        My research project is to investigate pre-training models with additional visual modalities by involving image embeddings in the pre-training steps, supervised by Pengchuan Zhang, Jianwei Yang, Chunyuan Li, Jianfeng Gao.

        
  - title: Research Intern, Computer Vision
    company: Microsoft AI & Cloud
    company_url: ''
    company_logo: org-ms
    location: Redmond, USA
    date_start: '2020-06-21'
    date_end: '2020-09-13'
    description: |2-
        My research project is to investigate pre-training models with additional visual modalities by involving image embeddings in the pre-training steps, supervised by Dinei Florencio, Yijuan Lu, Guoxin Wang.
        
        * Adopted a simple yet powerful Transformer model as the backbone and extends it to take both visual and text embedded features.
        * Designed the Masked Language Model (MLM) and Image-Text Matching (ITM) to jointly model interactions between language, layout and rich visual information.
        * Visual-LayoutLM model has shown its potential to outperform the original LayoutLM and other SOTA models in several document understanding tasks. 

design:
  columns: '2'
---
