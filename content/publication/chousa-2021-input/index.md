---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Input Augmentation Improves Constrained Beam Search for Neural Machine Translation: NTT at WAT 2021'
subtitle: ''
summary: ''
authors:
- Katsuki Chousa
- Makoto Morishita
tags: []
categories: []
date: '2021-06-11'
lastmod: 2021-06-11T09:59:37+09:00
featured: true
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
publishDate: '2021-06-11T00:59:32.871824Z'
publication_types:
- 1
abstract: "
    <span style='color:red'>**First place in all of the participated subtasks (ASPEC Ja-En, En-Ja)**</span><br>
    This paper describes our systems that were submitted to the restricted translation task at WAT 2021. In this task, the systems are required to output translated sentences that contain all given word constraints. Our system combined input augmentation and constrained beam search algorithms. Through experiments, we found that this combination significantly improves translation accuracy and can save inference time while containing all the constraints in the output. For both En->Ja and Ja->En, our systems obtained the best evaluation performances in automatic and human evaluation.
"

publication: 'Proceedings of the 8th Workshop on Asian Translation (WAT 2021)'

links:
- name: Paper
  url: https://aclanthology.org/2021.wat-1.3/
- name: arXiv
  url: https://arxiv.org/abs/2106.05450

---
