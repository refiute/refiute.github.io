---
title: 'JAPAS: 日本語特許のサポート関係抽出のためのベンチマークとニューラル手法'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- 帖佐 克己
- 杉浦 亮介

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2027-03-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2026-11-13T03:33:56.626842Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- journal

# Publication name and optional abbreviated publication name.
publication: '*自然言語処理*'
publication_short: ''

doi: ''

abstract: "<span style='color:red'>**(To appear)**</span><br>
           特許分析の基礎となる作業の一つに、請求項のどの記載が明細書のどの段落によって裏付けられているかを対応づける、サポート関係の抽出がある。
           この対応関係は、明細書が請求の範囲を十分に説明しているか（サポート要件）の法的な検証などに応用される。
           この作業は高度なドメイン知識と多大な労力を要するため自動化が望まれているが、(1) 公開されたベンチマークの不在、(2) 既存研究が語彙マッチングに依存し意味的等価性を捉えられない、という2つの課題が存在した。
           本研究では、これらを解決するために、日本語の特許文書を対象に2,000件以上の手動アノテーションを付与したデータセット「JAPAS」を構築した。
           さらに、本ベンチマーク上で、テキスト埋め込みおよび大規模言語モデルによる、意味的類似度を考慮したベースラインを確立した。
           実験の結果、JAPAS でファインチューニングした Qwen3-14B が請求項単位の F1 で 0.50 を達成し、最良の表層ベースラインから +0.14 ポイントの改善を示した。
           この結果は、JAPAS が本タスクにおいて効果的かつ高品質な研究基盤であることを示すと同時に、本タスクが実現可能でありながらも課題が残ることを示唆している。"

# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

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
