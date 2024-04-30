---
title: 'JParaCrawl v4.0: クラウドソーシングを併用した大規模対訳コーパスの構築'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- 森下 睦
- 帖佐 克己
- 永田 昌明

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-03-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-04-30T05:39:51.361782Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- report 

# Publication name and optional abbreviated publication name.
publication: '*言語処理学会第30回年次大会*'
publication_short: 'NLP2024'

doi: ''

abstract: "
  現在の機械翻訳モデルは主に対訳コーパスを用いて学習されており、その翻訳精度は対訳コーパスの質と量に大きく依存している。本稿では、新たにウェブをクロールし日英対訳文を抽出することで大規模日英対訳コーパスを構築し、翻訳精度の底上げを狙う。なおこの際クラウドソーシングを活用して対訳文が存在するウェブサイトを発見することで、効率的な対訳文収集を目指す。今回ウェブから収集した対訳文と以前作成した日英対訳コーパスJParaCrawl v3.0 を合わせることで、合計 4400 万文を超える日英最大規模の対訳コーパスを作成することに成功した。実験により、新たな対訳コーパスを用いて学習した翻訳モデルが様々な分野で高い翻訳精度を発揮することを示す。なお、今回作成した対訳コーパスを JParaCrawl v4.0 と名付け、我々のウェブサイト上で研究目的利用に限り無償公開する予定である。
"

# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: ''
url_code: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Custom links (uncomment lines below)
links:
- name: Paper 
  url: https://www.anlp.jp/proceedings/annual_meeting/2024/pdf_dir/P8-16.pdf
- name: Dataset
  url: 'http://www.kecl.ntt.co.jp/icl/lirg/jparacrawl/'

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