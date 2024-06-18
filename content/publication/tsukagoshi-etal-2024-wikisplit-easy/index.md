---
title: 'WikiSplit++: Easy Data Refinement for Split and Rephrase'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Hayato Tsukagoshi
- Tsutomu Hirao
- Makoto Morishita
- Katsuki Chousa
- Ryohei Sasano
- Koichi Takeda

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-05-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-06-18T04:01:45.923653Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: '*Proceedings of the 2024 Joint International Conference on Computational
  Linguistics, Language Resources and Evaluation (LREC-COLING 2024)*'
publication_short: ''

doi: ''

abstract: The task of Split and Rephrase, which splits a complex sentence into multiple
  simple sentences with the same meaning, improves readability and enhances the performance
  of downstream tasks in natural language processing (NLP). However, while Split and
  Rephrase can be improved using a text-to-text generation approach that applies encoder-decoder
  models fine-tuned with a large-scale dataset, it still suffers from hallucinations
  and under-splitting. To address these issues, this paper presents a simple and strong
  data refinement approach. Here, we create WikiSplit++ by removing instances in WikiSplit
  where complex sentences do not entail at least one of the simpler sentences and
  reversing the order of reference simple sentences. Experimental results show that
  training with WikiSplit++ leads to better performance than training with WikiSplit,
  even with fewer training instances. In particular, our approach yields significant
  gains in the number of splits and the entailment ratio, a proxy for measuring hallucinations.

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
  url: https://aclanthology.org/2024.lrec-main.1533
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
