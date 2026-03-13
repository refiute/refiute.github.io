---
title: 単一のhubテキストがCLIPを壊す：hubnessによるクロスモーダル埋め込みの脆弱性特定

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- 出口 祥之
- 帖佐 克己
- 坂井 優介

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2026-03-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2026-03-13T00:42:41.731858Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- report

# Publication name and optional abbreviated publication name.
publication: '*言語処理学会第32回年次大会 (NLP2026)*'
publication_short: ''

doi: ''

abstract: '無関係な多くの事例と高い類似度を示す hub 埋め込みは、埋め込みに基づく情報検索や品質評価指標などにおいてノイズとなる。特に、テキスト・画像のような直接比較できないモダリティ間の類似度計算は CLIP などの埋め込みに頼る必要があり、hubの存在はモデルの信頼性に影響する。本稿では、クロスモーダル埋め込みモデルの脆弱性を特定するため、hub 埋め込みに射影されてしまう hub テキストの探索法を提案する。画像キャプションの品質評価および画像テキスト検索実験より、単一の hub テキストが各画像ごとに個別に生成したキャプションより高い ClipScore を示し、また、hub テキストの混入により検索性能が大幅に低下することを確認した。'

# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: 'https://www.anlp.jp/proceedings/annual_meeting/2026/pdf_dir/B4-12.pdf'

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org


# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects: ['internal-project']` links to `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
