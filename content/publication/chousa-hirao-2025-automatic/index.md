---
title: Automatic Evaluation of Language Generation Technology Based on Structure Alignment

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Katsuki Chousa
- Tsutomu Hirao

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2025-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-01-21T05:17:43.077392Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: '*Proceedings of the 31st International Conference on Computational Linguistics*'
publication_short: ''

doi: ''

abstract: Language generation techniques require automatic evaluation to carry out
  efficient and reproducible experiments. While n-gram matching is standard, it fails
  to capture semantic equivalence with different wording. Recent methods have addressed
  this issue by using contextual embeddings from pre-trained language models to compute
  the similarity between reference and hypothesis. However, these methods frequently
  disregard the syntax of sentences, despite its crucial role in determining meaning,
  and thus assign unjustifiably high scores. This paper proposes an automatic evaluation
  metric that considers both the words in sentences and their syntactic structures.
  We integrate syntactic information into the recent embedding-based approach. Experimental
  results obtained from two NLP tasks show that our method is at least comparable
  to standard baselines.

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
  url: https://aclanthology.org/2025.coling-main.512/
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
