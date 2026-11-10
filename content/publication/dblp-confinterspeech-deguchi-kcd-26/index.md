---
title: Non-Autoregressive Minimum Bayes' Risk Decoding for Fast Speech Recognition

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Hiroyuki Deguchi
- Takatomo Kano
- Katsuki Chousa
- Marc Delcroix

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2026-09-30'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2026-11-10T11:56:42.529460Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: '*27th Annual Conference of the International Speech Communication Association,
  Interspeech 2026, Sydney, Australia, September 27 - October 1, 2025*'
publication_short: ''

doi: 10.21437/INTERSPEECH.2026-2971

abstract: "Non-autoregressive (NAR) decoding generates output tokens in parallel, making speech recognition faster than autoregressive decoding, which generates them sequentially from left to right. However, the recognition performance is degraded because NAR decoding cannot resolve uncertainty by conditioning on previously generated tokens. To address this issue, we propose a novel NAR decoding framework based on minimum Bayes' risk (MBR) decoding, termed NAR-MBR decoding, that maximizes the expected utility calculated from samples drawn from the output probability of an NAR model rather than maximizing the output probability. Notably, by leveraging the nature of NAR models, multiple samples are obtained efficiently with a single forward computation. Our experiments across LibriSpeech, Switchboard, AMI, and web presentation corpus demonstrated that our NAR-MBR decoding outperformed previous NAR decoding and ran faster than AR decoding."

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
  url: https://doi.org/10.21437/Interspeech.2026-2971
- name: arXiv
  url: https://arxiv.org/abs/2606.17537
---

