---
permalink: /
title: "About me"
excerpt: "Machine learning researcher working on biomolecular foundation models, structure prediction, and gene expression."
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% include base_path %}

I am a PhD student in Machine Learning at Mohamed bin Zayed University of Artificial Intelligence (MBZUAI), supervised by Prof. [Le Song](https://dasongle.github.io/), with expected completion in December 2026. My research focuses on biomolecular foundation models, structure prediction, gene expression prediction, and multimodal learning for biology. My thesis is *Representation Learning with Foundation Models for Biomolecular Structure and Function Prediction*.

I am also a research intern at GenBio AI. I previously visited the Sailing Lab at Carnegie Mellon University, hosted by Prof. [Eric P. Xing](https://www.cs.cmu.edu/~epxing/), and interned at BioMap.

I received my MSc in Computer Science from the University of Chinese Academy of Sciences (2019–2022), advised by Prof. [Jiajun Zhang](https://nlpr.ia.ac.cn/cip/jjzhang.htm). At the Institute of Automation, Chinese Academy of Sciences, I worked with Prof. [Chengqing Zong](https://nlpr.ia.ac.cn/cip/english/zong.htm), Prof. Zhang, and Dr. [Shaonan Wang](https://wangshaonan.github.io/) on decoding natural language from fMRI. Before graduate school, I worked as a data analyst at China Mobile (2014–2018), after completing my BSc in Statistics at Sun Yat-sen University (2010–2014).

[Download my CV (PDF)]({{ base_path }}/files/Shuxian_Zou_CV.pdf) · [View full CV]({{ base_path }}/cv/)

Research Interests
======

I develop self-supervised and multimodal learning methods to connect biological sequences with their structure and function. My current work includes:

* **RNA and protein foundation models:** core contributor to the 1.6B-parameter [GB.RNA](https://huggingface.co/collections/genbio-ai/gbrna) and 16B-parameter Mixture-of-Experts [GB.Protein](https://huggingface.co/collections/genbio-ai/gbprotein) models, with experience pretraining on 64 NVIDIA A100 GPUs.
* **Biomolecular structure prediction:** using language model representations to improve RNA 3D structure prediction and protein modeling.
* **Gene expression and multimodal biology:** predicting tissue-specific RNA isoform expression by integrating DNA, RNA, and protein data, including a [GTEx-derived transcript isoform expression dataset](https://huggingface.co/datasets/genbio-ai/transcript_isoform_expression_prediction).
* **Model adaptation and evaluation:** developing sequence-level tasks and multimodal fusion in [GB.ModelGenerator](https://github.com/genbio-ai/modelgenerator), and evaluating RNA models on more than 100 downstream tasks.

*I am open to collaborations and new opportunities!*

Research Experience
======

* **Research Intern, GenBio AI**, Abu Dhabi, UAE — December 2024–December 2025; June 2026–present (expected through December 2026).
* **Visiting PhD Student, Sailing Lab, Carnegie Mellon University**, Pittsburgh, USA — June–September 2024. Host: Prof. Eric P. Xing.
* **Algorithm Intern, BioMap**, Beijing, China — July–September 2023.
* **Research Assistant, Institute of Automation, Chinese Academy of Sciences**, Beijing, China — July 2019–May 2022.

Selected Publications and Preprints
======

{% include publication-list.md %}

Teaching and Awards
======

* **Teaching Assistant, MBZUAI:** Advanced Machine Learning (Spring 2025); Machine Learning with Python (Fall 2025, Fall 2026).
* **Outstanding Teaching Assistant Award**, MBZUAI, Spring 2025.

Competitions 
======

* Stanford RNA 3D Folding (Kaggle, 2025) — 6th place out of 1,516 teams (Gold Medal).
    - Team: Littletree🎄 & Moth & Bianco.
    - Contributors: **Shuxian Zou**, Alejo Paullier, Bingkang Zhao.
    - My contributions: Augment Protenix with AIDO.RNA embeddings to improve RNA 3D structure prediction.
    - [Solution write-up](https://www.kaggle.com/competitions/stanford-rna-3d-folding/writeups/6th-place-solution)
* The 3rd Magic Mirror Cup – Intelligent Customer Service Question Similarity Algorithm Design (2018) - 16th out of 359 teams in the first round; 12th out of 95 teams in the final round.
    - Team: moka_tree.
    - Contributors: Lei Zhu, **Shuxian Zou**.
    - My contributions: [Solution write-up (Chinese)](https://www.jianshu.com/p/827dd447daf9), [Github](https://github.com/LittletreeZou/Question-Pairs-Matching)
