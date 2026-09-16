---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download my CV (PDF)]({{ base_path }}/files/Shuxian_Zou_CV.pdf)

Research Profile
======

Machine learning researcher focused on biomolecular foundation models, structure, gene expression, and multimodal biology. Experience in self-supervised learning and distributed training with PyTorch, Megatron-LM, and Hugging Face, including pretraining on 64 NVIDIA A100 GPUs.

* Core contributor to 1.6B-parameter [GB.RNA](https://huggingface.co/collections/genbio-ai/gbrna) and 16B-parameter Mixture-of-Experts [GB.Protein](https://huggingface.co/collections/genbio-ai/gbprotein).
* Stanford RNA 3D Folding (Kaggle, 2025): Gold Medal, 6th/1,516 teams.

Education
======

### PhD in Machine Learning — Mohamed bin Zayed University of Artificial Intelligence

Abu Dhabi, UAE · 2022–Dec 2026 (expected)

* GPA: 3.95/4.00; full sponsorship.
* Thesis: *Representation Learning with Foundation Models for Biomolecular Structure and Function Prediction* (in progress).
* Advisor: Prof. Le Song.
* Thesis committee: Eric P. Xing, Kun Zhang, and Christoph Feinauer.

### MSc in Computer Science — University of Chinese Academy of Sciences

Beijing, China · 2019–2022

* GPA: 3.86/4.00; academic scholarship.
* Thesis: *Research on Decoding Natural Language from Functional Brain Images*.
* Advisor: Prof. Jiajun Zhang.

### BSc in Statistics — Sun Yat-sen University

Guangzhou, China · 2010–2014

* GPA: 4.0/5.0; top 10%.

Research Experience
======

### Research Intern — GenBio AI

Abu Dhabi, UAE · Dec 2024–Dec 2025; Jun 2026–present (expected end: Dec 2026)

* Developed [GB.RNA](https://huggingface.co/genbio-ai/GB.RNA-1.6B) and [GB.RNA-CDS](https://huggingface.co/genbio-ai/GB.RNA-1.6B-CDS) for noncoding RNA and coding sequences; evaluated them on 100+ structure, expression, and function tasks.
* Benchmarked [GB.Protein](https://huggingface.co/genbio-ai/GB.Protein-16B), [GB.Protein-RAG](https://huggingface.co/genbio-ai/GB.Protein-RAG-16B), and [GB.Protein2StructureToken](https://huggingface.co/genbio-ai/GB.Protein2StructureToken-16B) on ProteinGym DMS and xTrimoPGLM for protein understanding and fitness prediction.
* Curated a [GTEx transcript isoform dataset](https://huggingface.co/datasets/genbio-ai/transcript_isoform_expression_prediction); built multimodal models using DNA, RNA, and protein data to predict tissue-specific isoform expression.
* Added sequence-level tasks and multimodal fusion to [GB.ModelGenerator](https://github.com/genbio-ai/modelgenerator).
* Collaborated on wet-lab validation of designed RNA aptamers with the RNA design team and an external CRO.

### Visiting PhD Student — Sailing Lab, Carnegie Mellon University

Pittsburgh, USA · Jun–Sep 2024 · Host: Prof. Eric P. Xing

* Studied pretraining data and strategies for billion-parameter models spanning noncoding and protein-coding RNA.
* Explored efficient pretraining and evaluation of a 16B-parameter protein language model.

### Algorithm Intern — BioMap

Beijing, China · Jul–Sep 2023

* Pretrained cross-modal protein models on STRING interaction data with Megatron-LM for antibody–antigen binding affinity prediction.

### Research Assistant — Institute of Automation, Chinese Academy of Sciences

Beijing, China · Jul 2019–May 2022

* Developed fMRI-to-word and fMRI-to-text decoding tasks and methods using pretrained encoder–decoder models.

Selected Publications and Preprints
======

{% include publication-list.md %}

Teaching and Additional Experience
======

* **Teaching Assistant, MBZUAI:** Advanced Machine Learning (Spring 2025); Machine Learning with Python (Fall 2025, 2026).
* **Data Analyst, China Mobile**, Guangzhou, China — 2014–2018. Customer analysis and KPI project management.

Selected Awards
======

* **Gold Medal, Stanford RNA 3D Folding (Kaggle, 2025)** — 6th/1,516 teams. [Solution](https://www.kaggle.com/competitions/stanford-rna-3d-folding/writeups/6th-place-solution).
* **Outstanding Teaching Assistant Award**, MBZUAI, Spring 2025.

Skills
======

* **Programming:** Python, Shell, SQL.
* **Machine learning:** PyTorch, Megatron-LM, Hugging Face, Lightning, TensorFlow, scikit-learn.
* **HPC and infrastructure:** SLURM, Weights & Biases (W&B), distributed multi-GPU training.
* **Developer tools:** Git, Claude Code, Codex.
* **Languages:** English (professional proficiency), Chinese (native), Cantonese (fluent), Hakka (native).
