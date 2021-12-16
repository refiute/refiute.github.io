---
# Documentation: https://wowchemy.com/docs/managing-content/

title: A Supervised Word Alignment Method based on Cross-Language Span Prediction
  using Multilingual BERT
subtitle: ''
summary: ''
authors:
- Masaaki Nagata
- Katsuki Chousa
- Masaaki Nishino
tags: []
categories: []
date: '2020-11-01'
lastmod: 2020-10-04T22:08:29+09:00
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
publishDate: '2020-10-04T13:08:28.920953Z'
publication_types:
- 1
abstract: 'We present a novel supervised word alignment method based on cross-language span prediction. We first formalize a word alignment problem as a collection of independent predictions from a token in the source sentence to a span in the target sentence. As this is equivalent to a SQuAD v2.0 style question answering task, we then solve this problem by using multilingual BERT, which is fine-tuned on a manually created gold word alignment data. We greatly improved the word alignment accuracy by adding the context of the token to the question. In the experiments using five word alignment datasets among Chinese, Japanese, German, Romanian, French, and English, we show that the proposed method significantly outperformed previous supervised and unsupervised word alignment methods without using any bitexts for pretraining. For example, we achieved an F1 score of 86.7 for the Chinese-English data, which is 13.3 points higher than the previous state-of-the-art supervised methods.'
publication: 'Proceedings of the 2020 Conference on Empirical Methods in Natural Language Processing (EMNLP 2020)'

links:
- name: Paper
  url: https://www.aclweb.org/anthology/2020.emnlp-main.41/
- name: arXiv
  url: https://arxiv.org/abs/2004.14516
- name: Code
  url: https://github.com/nttcslab-nlp/word_align

---
