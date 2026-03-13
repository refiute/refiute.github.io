---
title: 'JAPAS: A Benchmark and Neural Approach for Japanese Patent S upport Relation Extraction'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Katsuki Chousa
- Ryosuke Sugiura

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2026-05-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2026-03-13T01:12:25.354664Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: 'Proceedings of the 15th biennial Language Resource and Evaluation Conference'
publication_short: 'LREC2026'

doi: ''

abstract: 'Efficient analysis of patent literature is crucial for technological development
  and protecting intellectual property. Akey task is verifying the “support requirement,”
  which mandates that the detailed description must fully describe theclaimed invention.
  This requirement is fundamental to a patent’s validity. Manual verification is a
  labor-intensiveprocess that demands technical and legal expertise, making automation
  highly desirable. However, research onthis task has been hampered by two key challenges:
  (1) the absence of a public benchmark, and (2) the reliance ofprior work on lexical
  matching, which fails to capture semantic equivalence. To address these issues,
  we introduceJAPAS, the first public benchmark for this task, comprising over 2,000
  instances manually annotated for Japanesepatents. Each instance is labeled with
  a claim span, a supporting description paragraph, a relation type, and theannotator’s
  confidence level. Using this benchmark, we also establish modern baselines that
  capture semanticsimilarity, such as embeddings and LLMs. Our experiments show that
  a fine-tuned Qwen3-14B model achieves anF1 score of 0.50, outperforming the conventional
  lexical-based baseline. This result, which demonstrates that thetask is feasible
  yet challenging, highlights the utility of JAPAS as a research foundation and provides
  a performancetarget for future work.'

# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in a list of Featured pages?
featured: true

# Links
url_dataset: 'https://www.kecl.ntt.co.jp/icl/lirg/japas/'

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
