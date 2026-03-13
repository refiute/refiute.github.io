---
title: Hacking Neural Evaluation Metrics with Single Hub Text

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Hiroyuki Deguchi
- Katsuki Chousa
- Yusuke Sakai

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2026-03-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2026-03-13T00:35:16.679922Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: 'Proceedings of the 19th Conference of the European Chapter of the Association for Computational Linguistics'
publication_short: 'EACL2026'

doi: ''

abstract: Strongly human-correlated evaluation metrics serve as an essential compass
  for the development and improvement of generation models and must be highly reliable
  and robust. Recent embedding-based neural text evaluation metrics, such as COMET
  for translation tasks, are widely used in both research and development fields.
  However, there is no guarantee that they yield reliable evaluation results due to
  the black-box nature of neural networks. To raise concerns about the reliability
  and safety of such metrics, we propose a method for finding a single adversarial
  text in the discrete space that is consistently evaluated as high-quality, regardless
  of the test cases, to identify the vulnerabilities in evaluation metrics. The single
  hub text found with our method achieved 79.1 COMET% and 67.8 COMET% in the WMT'24
  English-to-Japanese (En--Ja) and English-to-German (En--De) translation tasks, respectively,
  outperforming translations generated individually for each source sentence by using
  M2M100, a general translation model. Furthermore, we also confirmed that the hub
  text found with our method generalizes across multiple language pairs such as Ja--En
  and De--En.

# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in a list of Featured pages?
featured: true

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

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects: ['internal-project']` links to `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
links:
- name: arXiv
  url: https://arxiv.org/abs/2512.16323
---

