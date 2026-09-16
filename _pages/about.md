---
permalink: /
title: "About me"
excerpt: "Biomolecular foundation models, structure prediction, and gene expression."
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

{% include base_path %}

I’m a Machine Learning PhD student at MBZUAI (expected Dec 2026), advised by Prof. [Le Song](https://dasongle.github.io/). I study biomolecular foundation models for structure, gene expression, and multimodal biology.

I’m a research intern at GenBio AI, with prior roles at Carnegie Mellon University’s Sailing Lab (host: Prof. [Eric P. Xing](https://www.cs.cmu.edu/~epxing/)) and BioMap.

I earned my MSc in Computer Science at the University of Chinese Academy of Sciences, advised by Prof. [Jiajun Zhang](https://nlpr.ia.ac.cn/cip/jjzhang.htm). At the Institute of Automation, I studied fMRI-to-language decoding with Prof. [Chengqing Zong](https://nlpr.ia.ac.cn/cip/english/zong.htm), Prof. Zhang, and Dr. [Shaonan Wang](https://wangshaonan.github.io/). I hold a BSc in Statistics from Sun Yat-sen University.

[View full CV]({{ base_path }}/cv/)

Research Interests
======

I use self-supervised and multimodal learning to link biological sequences to structure and function.

* **Foundation models:** core contributor to 1.6B-parameter [GB.RNA](https://huggingface.co/collections/genbio-ai/gbrna) and 16B-parameter Mixture-of-Experts [GB.Protein](https://huggingface.co/collections/genbio-ai/gbprotein), with pretraining experience on 64 NVIDIA A100 GPUs.
* **Structure prediction:** improving RNA 3D prediction and protein modeling with language model representations.
* **Gene expression:** predicting tissue-specific RNA isoform expression from DNA, RNA, and protein data; curating a [GTEx-derived dataset](https://huggingface.co/datasets/genbio-ai/transcript_isoform_expression_prediction).
* **Model adaptation:** sequence-level tasks and multimodal fusion in [GB.ModelGenerator](https://github.com/genbio-ai/modelgenerator); RNA and protein evaluation on 200+ tasks.

*Interested in RNA foundation models for mRNA therapeutics and virtual cell modeling. Seeking Research Scientist or Research Engineer roles in Europe and the US; open to collaborations.*

Research Experience
======

* **Research Intern, GenBio AI**, Abu Dhabi, UAE — Dec 2024–Dec 2025; Jun 2026–present.
* **Visiting PhD Student, Sailing Lab, Carnegie Mellon University**, Pittsburgh, USA — Jun–Sep 2024. Host: Prof. Eric Xing.
* **Algorithm Intern, BioMap**, Beijing, China — Jul–Sep 2023.
* **Research Assistant, Institute of Automation, Chinese Academy of Sciences**, Beijing, China — Jul 2019–May 2022.

Publications and Preprints
======

{% include publication-list.md %}

Competitions
======

* Stanford RNA 3D Folding (Kaggle, 2025) — Gold Medal, 6th/1,516 teams.
    - Team: Littletree🎄 & Moth & Bianco.
    - Contributors: **Shuxian Zou**, Alejo Paullier, Bingkang Zhao.
    - Contribution: augmented Protenix with AIDO.RNA embeddings for RNA 3D prediction.
    - [Solution write-up](https://www.kaggle.com/competitions/stanford-rna-3d-folding/writeups/6th-place-solution)
* 3rd Magic Mirror Cup — Customer Service Question Similarity (2018): 16th/359 teams (first round); 12th/95 (final).
    - Team: moka_tree.
    - Contributors: Lei Zhu, **Shuxian Zou**.
    - [Solution (Chinese)](https://www.jianshu.com/p/827dd447daf9) · [GitHub](https://github.com/LittletreeZou/Question-Pairs-Matching)
