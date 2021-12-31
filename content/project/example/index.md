---
title: 高光谱遥感图像多源混合噪声去噪关键技术
summary: 基于多分辨率密集记忆网络的高光谱图像去噪.
tags:
- Deep Learning
- Hyperspectral Image Denoising
date: "2021-08-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by LKP
  focal_point: Smart

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://github.com/lkp520
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

基于最优控制的思想以及受到HRNet和DenseNet的启发，我们首先设计了一个空间-光谱信息提取模块，随后利用平均池化将特征图分为4个不同分辨率，分别在不同的分辨率上提取特征，同时在卷积层之前加入门控层，用于学习是否进行跨分辨率的信息交互，在卷积层之后加入幂律记忆层，用于密集连接当前分辨率不同层的输出特征图来增强特征表示。此外，利用反卷积进行上采样，从而恢复图像大小。最后的重建层利用多尺度空洞卷积增大感受野，因而更好地恢复噪声高光谱图像。与SOTA方法对比，我们的方法能去除多种类型噪声，在高光谱遥感图像的模拟与真实数据实验中取得了先进的去噪性能。


