---
title: Improving Japanese-English Patent Claim Translation via Reasoning and GRPO
  with Syntactic Reward

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Shogo Tsujimoto
- Katsuki Chousa
- Masaaki Nagata
- Ryohei Sasano

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2026-11-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2026-11-10T11:56:27.681013Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: '*Proceedings of the 15th International Joint Conference on Natural Language
  Processing and the 5th Conference of the Asia-Pacific Chapter of the Association
  for Computational Linguistics (Volume 2: Short Papers)*'
publication_short: ''

doi: ''

abstract: 'Patent claims are legal documents with distinctive formats and complex syntactic dependencies. Translating these claims requires not only accurately understanding the complex syntactic structure of the source claims but also ensuring the translation follows the structural conventions of claims in the target language. In this study, we leverage reasoning models to disentangle the complex syntactic structures of source claims. Furthermore, to ensure the translation reflects the structural requirements in the target language, we incorporate FastKASSIM—a syntactic similarity metric—into the reward of reinforcement learning, alongside conventional metrics such as BLEU and COMET. Experimental results confirm that our model, trained on Qwen3-8B, outperforms Qwen3-235B in syntactic similarity while simultaneously achieving comparable translation quality, despite the latter having approximately 30 times more parameters. Automatic and human evaluations show that models trained with rewards combining FastKASSIM and translation quality metrics such as COMET or COMETKiwi achieve strong performance, suggesting that syntactic rewards help improve patent-specific structural conformity while maintaining translation quality.'

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
links:
- name: URL
  url: https://aclanthology.org/2026.aacl-short.9/
---
