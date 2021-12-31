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
  - title: 图像增强算法实习生
    company: 格灵人工智能与机器人研究院
    company_url: 'http://www.szglint.com/'
    company_logo: org-gc
    location: Shenzhen
    date_start: '2021-07-12'
    date_end: '2021-09-10'
    description: |2-
        Tasks include:
        
        * 图像上色：基于DeOldify(NoGAN+Self Attention的PyTorch改进版)对ImageNet数据集进行彩色化、基于InstColorization(实例分割+上色融合)对 Supervisely人像数据集上色；
        * 人像分割：收集人像分割数据集(Supervisely)，使用UNet+EfficientNet对其进行测试，得到人像的Masks.
        
  - title: 科创先锋
    company: 博智林机器人
    company_url: 'https://www.bzlrobot.com/'
    company_logo: org-x
    location: Foshan
    date_start: '2022-07-01'
    date_end: ''
    description: Artificial intelligence algorithm.

design:
  columns: '2'
---
