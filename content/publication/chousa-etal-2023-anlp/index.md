---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 部分木の類似性に基づく言語生成技術の自動評価
subtitle: ''
summary: ''
authors:
- 帖佐 克己
- 平尾 努
tags: []
categories: []
date: '2023-03-01'
lastmod: 2023-03-17T16:52:15+09:00
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
publishDate: '2023-03-17T07:52:15.285417Z'
publication_types:
- '4'
abstract: "
  系列変換モデルの発展により，言語生成技術の性能は飛躍的に向上し，多様な表現で流暢な文を生成できるようになってきた．言語生成技術をさらに発展させるには自動評価法が必要となるが，単語の一致に基づく従来の自動評価法は参照テキストと同じ意味を持つテキストであっても表現が異なれば低いスコアしか与えられない．一方，単語埋め込みベクトルを活用した自動評価法は，単語の類似性を重視するため，似たような単語列であれば意味が違っても高いスコアを与える．こうした問題を解決するため，本稿では，2 つの文の間の類似性を構文木の類似性に基づき決定する手法を提案する．WMTMetric Shared Task のデータセットを用いて人手評価との間の相関を調べた結果，提案法は教師データを必要にしないにもかかわらず，既存手法と同等以上の高い相関を達成した．
"
publication: '*言語処理学会第29回年次大会 (NLP2023)*'

links:
- name: Paper
  url: https://www.anlp.jp/proceedings/annual_meeting/2023/pdf_dir/P12-11.pdf
---
