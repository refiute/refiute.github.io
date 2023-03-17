---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 文脈情報を考慮した高速な日英文アラインメント
subtitle: ''
summary: ''
authors:
- 福田 りょう
- 帖佐 克己
tags: []
categories: []
date: '2023-03-01'
lastmod: 2023-03-17T16:52:22+09:00
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
publishDate: '2023-03-17T07:52:22.932751Z'
publication_types:
- '4'
abstract: "
  本論文では大規模対訳コーパスの作成に向けた高精度かつ高速な文アラインメント手法を提案する．従来手法では文外文脈およびトークン単位の情報を予測時に考慮することで高精度な文アラインメントを実現していたが，予測時の計算量が大きいことから大規模なデータへの適用が難しかった．本論文では，両方の言語の文脈情報を考慮した文ベクトルを用いて対訳文書間の全てのアラインメントを同時に予測することで，小さい計算量で高精度な文アラインメントを獲得する手法を提案する．日英での新聞記事を用いた実験により，提案手法が予測速度を維持しながら高い精度でアラインメントを行えることを示した．
"
publication: '*言語処理学会第29回年次大会 (NLP2023)*'

links:
- name: Paper
  url: https://www.anlp.jp/proceedings/annual_meeting/2023/pdf_dir/P6-6.pdf
---
