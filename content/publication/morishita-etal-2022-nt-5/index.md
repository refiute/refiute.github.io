---
# Documentation: https://wowchemy.com/docs/managing-content/

title: NT5 at WMT 2022 General Translation Task
subtitle: ''
summary: ''
authors:
- Makoto Morishita
- Keito Kudo
- Yui Oka
- Katsuki Chousa
- Shun Kiyono
- Sho Takase
- Jun Suzuki
tags: []
categories: []
date: '2022-12-01'
lastmod: 2023-01-12T16:23:55+09:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2023-01-12T07:23:54.712136Z'
publication_types:
- 1
abstract: "
This paper describes the NTT-TohokuTokyoTech-RIKEN (NT5) team’s submission system for the WMT’22 general translation task. This year, we focused on the English-toJapanese and Japanese-to-English translation tracks. Our submission system consists of an ensemble of Transformer models with several extensions. We also applied data augmentation and selection techniques to obtain potentially effective training data for training individual Transformer models in the pre-training and fine-tuning scheme. Additionally, we report our trial of incorporating a reranking module and the reevaluated results of several techniques that have been recently developed and published.
"
publication: '*Proceedings of the Seventh Conference on Machine Translation*'

links:
- name: Paper
  url: https://www.statmt.org/wmt22/pdf/2022.wmt-1.25.pdf
---
