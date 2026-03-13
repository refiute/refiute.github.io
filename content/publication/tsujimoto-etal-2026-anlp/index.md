---
title: 構文類似度報酬を用いたGRPOを適用したReasoningモデルによる特許請求項の日英翻訳

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- 辻本 祥吾
- 帖佐 克己
- 永田 昌明
- 笹野 遼平

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2026-03-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2026-03-13T00:48:44.904896Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- report

# Publication name and optional abbreviated publication name.
publication: '*言語処理学会第32回年次大会 (NLP2026)*'
publication_short: ''

doi: ''

abstract: '特許請求項は，独特な書式と複雑な構文構造を持つ法的文書である．そのため，その翻訳には，原文の複雑な構文構造を正確に理解するだけでなく，翻訳先言語における特許固有の構文構造に従うことが求められる．本研究では，原文の構文構造をより正確に捉えるために Reasoning モデルを活用し，翻訳先言語における特許固有の構文構造を翻訳に反映させるために，構文構造の類似度を測る FastKASSIMを従来の BLEU や COMET といった評価尺度とともに強化学習の報酬として組み込む．実験の結果，Qwen3-8B をベースに学習したモデルが，約 30 倍の規模の Qwen3-235B ベースのモデルに匹敵する，あるいは上回る性能を達成した．また，FastKASSIMを報酬に用いることが，翻訳先言語での構文構造を反映した翻訳に寄与することを定性的に示した．'

# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: 'https://www.anlp.jp/proceedings/annual_meeting/2026/pdf_dir/C8-12.pdf'

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# Publication image
# Add an image named `featured.jpg/png` to your page's folder then add a caption below.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects: ['internal-project']` links to `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
