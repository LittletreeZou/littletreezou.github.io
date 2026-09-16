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

Machine learning researcher specializing in biomolecular foundation models, structure prediction, gene expression prediction, and multimodal learning for biology. Experienced in self-supervised learning and large-scale distributed training with PyTorch, Megatron-LM, and Hugging Face, including pretraining on 64 NVIDIA A100 GPUs.

* Core contributor to the 1.6B-parameter [GB.RNA](https://huggingface.co/collections/genbio-ai/gbrna) foundation model and the 16B-parameter Mixture-of-Experts [GB.Protein](https://huggingface.co/collections/genbio-ai/gbprotein) model.
* Gold Medalist in the 2025 Stanford RNA 3D Folding Kaggle Competition, ranked 6th out of 1,516 teams.

Education
======

### PhD in Machine Learning — Mohamed bin Zayed University of Artificial Intelligence

Abu Dhabi, UAE · 2022–December 2026 (expected)

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

Abu Dhabi, UAE · December 2024–December 2025; June 2026–present (expected through December 2026)

* Developed [GB.RNA](https://huggingface.co/genbio-ai/GB.RNA-1.6B) and [GB.RNA-CDS](https://huggingface.co/genbio-ai/GB.RNA-1.6B-CDS), foundation models for noncoding RNA and coding sequences, and evaluated them on more than 100 downstream tasks spanning RNA structure, expression, and function prediction.
* Benchmarked [GB.Protein](https://huggingface.co/genbio-ai/GB.Protein-16B), [GB.Protein-RAG](https://huggingface.co/genbio-ai/GB.Protein-RAG-16B), and [GB.Protein2StructureToken](https://huggingface.co/genbio-ai/GB.Protein2StructureToken-16B) on ProteinGym DMS and xTrimoPGLM benchmarks for protein understanding and fitness prediction.
* Curated a [transcript isoform expression dataset](https://huggingface.co/datasets/genbio-ai/transcript_isoform_expression_prediction) from GTEx and developed multimodal models for tissue-specific RNA isoform expression prediction, integrating DNA, RNA, and protein data.
* Implemented sequence-level tasks and multimodal fusion in [GB.ModelGenerator](https://github.com/genbio-ai/modelgenerator), a framework for adapting pretrained biological models to downstream scientific tasks.
* Collaborated with the RNA design team and an external contract research organization to experimentally validate designed RNA aptamers through wet-lab assays.

### Visiting PhD Student — Sailing Lab, Carnegie Mellon University

Pittsburgh, USA · June–September 2024 · Host: Prof. Eric P. Xing

* Investigated pretraining data and strategies to scale RNA foundation models to billions of parameters and enable unified modeling of noncoding and protein-coding RNA sequences.
* Explored efficient pretraining and downstream evaluation strategies for a 16B-parameter protein language model.

### Algorithm Intern — BioMap

Beijing, China · July–September 2023

* Pretrained cross-modal protein models on large-scale STRING protein–protein interaction data using Megatron-LM for antibody–antigen binding affinity prediction.

### Research Assistant — Institute of Automation, Chinese Academy of Sciences

Beijing, China · July 2019–May 2022

* Proposed new tasks and methods for fMRI-based brain-to-word and brain-to-text decoding using pretrained encoder–decoder language models.

Selected Publications and Preprints
======

{% include publication-list.md %}

Teaching and Additional Experience
======

* **Teaching Assistant, MBZUAI:** Advanced Machine Learning (Spring 2025); Machine Learning with Python (Fall 2025, Fall 2026).
* **Data Analyst, China Mobile**, Guangzhou, China — 2014–2018. Customer analysis and KPI project management.

Selected Awards
======

* **Gold Medal, Stanford RNA 3D Folding Kaggle Competition**, 2025 — ranked 6th out of 1,516 teams. [Solution write-up](https://www.kaggle.com/competitions/stanford-rna-3d-folding/writeups/6th-place-solution).
* **Outstanding Teaching Assistant Award**, MBZUAI, Spring 2025.

Skills
======

* **Programming:** Python, Shell, SQL.
* **Machine learning:** PyTorch, Megatron-LM, Hugging Face, Lightning, TensorFlow, scikit-learn.
* **HPC and infrastructure:** SLURM, Weights & Biases (W&B), distributed multi-GPU training.
* **Developer tools:** Git, Claude Code, Codex.
* **Languages:** English (professional proficiency), Chinese (native), Cantonese (fluent), Hakka (native).
