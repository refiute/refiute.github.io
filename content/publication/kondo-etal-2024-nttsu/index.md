---
title: NTTSU at WMT2024 General Translation Task

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Minato Kondo
- Ryo Fukuda
- Xiaotian Wang
- Katsuki Chousa
- Masato Nishimura
- Kosei Buma
- Takatomo Kano
- Takehito Utsuro

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-11-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-12-11T06:37:26.772731Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: '*Proceedings of the Ninth Conference on Machine Translation*'

doi: 10.18653/v1/2024.wmt-1.20

abstract: " 
  <span style='color:red'>**First place in the English-Japanese task**</span><br>
  The NTTSU team′s submission leverages several large language models developed through a training procedure that includes continual pre-training and supervised fine-tuning. For paragraph-level translation, we generated synthetic paragraph-aligned data and utilized this data for training.In the task of translating Japanese to Chinese, we particularly focused on the speech domain translation. Specifically, we built Whisper models for Japanese automatic speech recognition (ASR). We used YODAS dataset for Whisper training. Since this data contained many noisy data pairs, we combined the Whisper outputs using ROVER for polishing the transcriptions. Furthermore, to enhance the robustness of the translation model against errors in the transcriptions, we performed data augmentation by forward translation from audio, using both ASR and base translation models.To select the best translation from multiple hypotheses of the models, we applied Minimum Bayes Risk decoding + reranking, incorporating scores such as COMET-QE, COMET, and cosine similarity by LaBSE.
"

# Display this page in a list of Featured pages?
featured: true 

links:
- name: Paper 
  url: https://aclanthology.org/2024.wmt-1.20
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
