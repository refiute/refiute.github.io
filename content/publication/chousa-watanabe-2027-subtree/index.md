---
title: Subtree Constraints for Syntactically Controlled Paraphrase Generation

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Katsuki Chousa
- Taro Watanabe

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2027-03-09'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2026-11-13T03:21:16.376056Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: '*Proceedings of the 20th Conference of the European Chapter of the Association
  for Computational Linguistics*'
publication_short: 'EACL2027'

doi: ''

abstract: "<span style='color:red'>**(To appear)**</span><br>
  Syntactically controlled paraphrase generation rewrites a sentence into
  a paraphrase with a specified syntactic structure. Existing methods specify the
  target structure as a single skeleton, typically a constituency tree pruned at a
  fixed height, which over-specifies unrelated structure and cannot express partial
  or multiple requirements. We instead propose emph subtree constraints: a set of
  wildcard regular expressions over a constituency tree's S-expression, each requiring
  a substructure somewhere in the tree, which strictly generalize the single skeleton.
  The constraints go directly into a prompt, and Qwen3-14B satisfies most of them
  by reasoning first, though reasoning is costly at inference. Because satisfaction
  is checked mechanically, we use it as a verifiable reward and train with GRPO on
  constraints extracted from parsed paraphrase pairs. The trained answer-only model
  matches or exceeds the reasoning baseline's constraint satisfaction with about 1/14--1/17
  as many output tokens. The control transfers across languages: training on English
  alone improves the four non-English PAWS-X languages over the answer-only base model,
  and multilingual training improves them further, bringing meaning preservation nearly
  on par with English. Without a reference paraphrase, reusing the constraints of
  the input's nearest neighbor in a precomputed bank performs on par with reference-derived ones."


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

