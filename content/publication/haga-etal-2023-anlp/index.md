---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 画像キャプショニングのための制約語の抽出法
subtitle: ''
summary: ''
authors:
- 芳賀 あかり
- 平尾 努
- 帖佐 克己
- 本田 右京
- 出口 祥之
- 渡辺 太郎
tags: []
categories: []
date: '2023-03-01'
lastmod: 2023-03-17T16:52:26+09:00
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
publishDate: '2023-03-17T07:52:26.645651Z'
publication_types:
- '4'
abstract: "
  従来の画像キャプショニングには画像とは無関係の語を含むキャプションをしばしば生成するという問題がある．これを解決するため，画像に関連する語をあらかじめ与えた上でキャプションを生成する手法が提案されているが，その自動決定法については議論がされていない．本研究では，物体検出器が出力するラベル (物体名) をその信頼度スコアと顕著性スコアを組み合わせてランキングすることでキャプションに含めるべき語を決定する手法を提案する．提案法で得た単語と人手生成の正解キャプション中の単語を比較した結果，自動抽出した単語のうち半数程度はキャプションに含まれていた．さらに人手評価を行ったところ，キャプションには含まれない単語であっても，その多くはキャプション生成が可能な程度に画像に関連した語であることがわかった．
"
publication: '*言語処理学会第29回年次大会 (NLP2023)*'

links:
- name: Paper
  url: https://www.anlp.jp/proceedings/annual_meeting/2023/pdf_dir/H9-2.pdf
---
