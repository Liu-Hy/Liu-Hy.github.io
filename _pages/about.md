---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a PhD student in Informatics at the School of Information Sciences, University of Illinois Urbana-Champaign, advised by Prof. [Bertram Ludäscher](https://ischool.illinois.edu/people/bertram-ludaescher).

My research interests include **Neuro-Symbolic AI**, **LLM Agents**, and **Data-Efficient Learning**. I aim to do research that is both theoretically grounded and practically effective, with a particular interest in combining formal methods with LLM agents for trustworthy reasoning and automation, with applications in biomedical and legal domains.

You can find my publications on <a href='https://scholar.google.com/citations?user=1jLWSKAAAAAJ'>Google Scholar <img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.


# Publications

- **GenoMAS: A Multi-Agent Framework for Scientific Discovery via Code-Driven Gene Expression Analysis**
  **Haoyang Liu**, Yao Li, Haohan Wang
  *arXiv preprint*, 2025

- **Dataset Distillation via the Wasserstein Metric**
  **Haoyang Liu**, Yao Li, Tianyu Xing, Peng Wang, Vikram Dalal, Liang Li, Jingrui He, Haohan Wang
  *ICCV 2025*

- **GenoTEX: An LLM Agent Benchmark for Automated Gene Expression Data Analysis**
  **Haoyang Liu**, Shuyu Chen, Ye Zhang, Haohan Wang
  *The 20th Machine Learning in Computational Biology Conference (MLCB 2025, Oral)*

- **Approximate Nullspace Augmented Finetuning for Robust Vision Transformers**
  **Haoyang Liu**, Aditya Singh, Yao Li, Haohan Wang
  *CPAL 2025 (Oral)*

- **Towards Adversarially Robust Dataset Distillation by Curvature Regularization**
  Eric Xue, Yao Li, **Haoyang Liu**, Yang Shen, Haohan Wang
  *AAAI 2025*

- **Foundation Model-Oriented Robustness: Robust Image Model Evaluation with Pretrained Models**
  Peiyan Zhang, **Haoyang Liu**, Chaozhuo Li, Xing Xie, Sunghun Kim, Haohan Wang
  *ICLR 2024*

- **Towards Trustworthy and Aligned Machine Learning: A Data-Centric Survey with Causality Perspectives**
  **Haoyang Liu**, Malay Chaudhary, Haohan Wang
  *arXiv preprint*, 2023

- **UIUC_BioNLP at SemEval-2021 Task 11: A Cascade of Neural Models for Structuring Scholarly NLP Contributions**
  **Haoyang Liu**, Maria Joann Sarol, Halil Kilicoglu
  *SemEval 2021* **(Best System Paper Award)**


# Education
- *2023 - Present*, Ph.D. in Informatics, University of Illinois Urbana-Champaign


# Contact
Feel free to reach out via email at haoyang6@illinois.edu.
