---
title: 'JaParaPat: A Large-Scale Japanese-English Parallel Patent Application Corpus'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Masaaki Nagata
- Makoto Morishita
- Katsuki Chousa
- Norihito Yasuda

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-05-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-06-18T04:01:41.187864Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: '*Proceedings of the 2024 Joint International Conference on Computational
  Linguistics, Language Resources and Evaluation (LREC-COLING 2024)*'
publication_short: ''

doi: ''

abstract: We constructed JaParaPat (Japanese-English Parallel Patent Application Corpus),
  a bilingual corpus of more than 300 million Japanese-English sentence pairs from
  patent applications published in Japan and the United States from 2000 to 2021.
  We obtained the publication of unexamined patent applications from the Japan Patent
  Office (JPO) and the United States Patent and Trademark Office (USPTO). We also
  obtained patent family information from the DOCDB, that is a bibliographic database
  maintained by the European Patent Office (EPO). We extracted approximately 1.4M
  Japanese-English document pairs, which are translations of each other based on the
  patent families, and extracted about 350M sentence pairs from the document pairs
  using a translation-based sentence alignment method whose initial translation model
  is bootstrapped from a dictionary-based sentence alignment. We experimentally improved
  the accuracy of the patent translations by 20 bleu points by adding more than 300M
  sentence pairs obtained from patent applications to 22M sentence pairs obtained
  from the web.

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
  url: https://aclanthology.org/2024.lrec-main.826
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
