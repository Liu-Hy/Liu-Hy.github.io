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

I am a PhD student in Informatics at the School of Information Sciences, University of Illinois Urbana-Champaign, advised by Prof. [Bertram Ludäscher](https://scholar.google.com/citations?user=nYx9xasAAAAJ&hl=en).

My research interests include **Neuro-Symbolic AI**, **LLM Agents**, and **Data-Efficient Learning**, with a particular interest in combining formal methods with LLM agents for trustworthy reasoning and automation, with applications in biomedical and legal domains.

You can find my publications on <a href='https://scholar.google.com/citations?user=1jLWSKAAAAAJ'>Google Scholar <img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.


# Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2025</div><a href="images/paper1_full.png" target="_blank"><img src='images/paper1_thumb.jpg' alt="GenoMAS" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

**GenoMAS: A Multi-Agent Framework for Scientific Discovery via Code-Driven Gene Expression Analysis**

**Haoyang Liu**, Yijiang Li, Haohan Wang

*arXiv preprint*, 2025

A multi-agent framework that combines workflow controllability with agentic autonomy for automated gene expression analysis. Features a guided-planning mechanism that enables agents to dynamically advance, revise, or backtrack while maintaining logical coherence.

[[arXiv]](https://arxiv.org/abs/2507.21035) [[Code]](https://github.com/Liu-Hy/GenoMAS) [[Project]](https://liu-hy.github.io/GenoMAS/)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><a href="images/paper2_full.png" target="_blank"><img src='images/paper2_thumb.jpg' alt="WMDD" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

**Dataset Distillation via the Wasserstein Metric**

**Haoyang Liu**, Yijiang Li, Tiancheng Xing, Vibhu Dalal, Luwei Li, Jingrui He, Haohan Wang

*IEEE/CVF International Conference on Computer Vision (ICCV)*, 2025

Leverages optimal transport theory for dataset distillation, using Wasserstein barycenter to preserve geometric characteristics of the original data distribution. Achieves consistent state-of-the-art performance across multiple high-resolution benchmarks.

[[Paper]](https://openaccess.thecvf.com/content/ICCV2025/html/Liu_Dataset_Distillation_via_the_Wasserstein_Metric_ICCV_2025_paper.html) [[arXiv]](https://arxiv.org/abs/2311.18531) [[Code]](https://github.com/Liu-Hy/WMDD) [[Project]](https://liu-hy.github.io/WMDD/)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MLCB 2025</div><a href="images/paper3_full.jpg" target="_blank"><img src='images/paper3_thumb.jpg' alt="GenoTEX" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

**GenoTEX: An LLM Agent Benchmark for Automated Gene Expression Data Analysis** ⭐ *Oral (14.4%)*

**Haoyang Liu**, Shuyu Chen, Ye Zhang, Haohan Wang

*The 20th Machine Learning in Computational Biology Conference (MLCB)*, 2025

A benchmark for evaluating LLM agents on automated gene expression analysis, featuring 913 real-world datasets with realistic complexities covering 132 human traits.

[[arXiv]](https://arxiv.org/abs/2406.15341) [[Code]](https://github.com/Liu-Hy/GenoTEX) [[Project]](https://liu-hy.github.io/GenoTEX/)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CPAL 2025</div><a href="images/paper4_full.png" target="_blank"><img src='images/paper4_thumb.jpg' alt="NAF" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

**Approximate Nullspace Augmented Finetuning for Robust Vision Transformers** ⭐ *Oral (12.7%)*

**Haoyang Liu**, Aditya Singh, Yijiang Li, Haohan Wang

*The 2nd Conference on Parsimony and Learning (CPAL)*, 2025

Generalizes the nullspace concept from linear layers to non-linear ViT encoder blocks, enabling robustness improvements via nullspace-augmented finetuning that enhances both adversarial and natural robustness simultaneously.

[[arXiv]](https://arxiv.org/abs/2403.10476) [[OpenReview]](https://openreview.net/forum?id=zH3Zwx3dLQ)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025</div><a href="images/paper5_full.png" target="_blank"><img src='images/paper5_thumb.jpg' alt="GUARD" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

**Towards Adversarially Robust Dataset Distillation by Curvature Regularization**

Eric Xue, Yijiang Li, **Haoyang Liu**, Yang Shen, Haohan Wang

*The 39th AAAI Conference on Artificial Intelligence (AAAI)*, 2025

Embeds adversarial robustness into distilled datasets via curvature regularization. Minimizes loss landscape curvature during distillation, reducing adversarial vulnerability with significantly less overhead than adversarial training.

[[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/32978) [[arXiv]](https://arxiv.org/abs/2403.10045) [[Code]](https://github.com/yumozi/GUARD)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2024</div><a href="images/paper6_full.png" target="_blank"><img src='images/paper6_thumb.jpg' alt="FMOR" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

**Foundation Model-oriented Robustness: Robust Image Model Evaluation with Pretrained Models**

Peiyan Zhang, **Haoyang Liu**, Chaozhuo Li, Xing Xie, Sunghun Kim, Haohan Wang

*The 12th International Conference on Learning Representations (ICLR)*, 2024

A dynamic robustness evaluation protocol using foundation models as surrogate oracles, enabling evaluation beyond fixed benchmarks through semantically bounded perturbations.

[[Paper]](https://openreview.net/forum?id=jd5GokdySz) [[arXiv]](https://arxiv.org/abs/2308.10632)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2023</div><a href="images/paper7_full.png" target="_blank"><img src='images/paper7_thumb.jpg' alt="Trustworthy ML Survey" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

**Towards Trustworthy and Aligned Machine Learning: A Data-centric Survey with Causality Perspectives**

**Haoyang Liu**, Maheep Chaudhary, Haohan Wang

*arXiv preprint*, 2023

A data-centric survey on trustworthy ML covering robustness, security, interpretability, and fairness, unified through Pearl's causal hierarchy.

[[arXiv]](https://arxiv.org/abs/2307.16851) [[Project]](https://trustworthyartificialintelligence.github.io/papers/trustworthyMLsurvey.html)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SemEval 2021</div><a href="images/paper8_full.png" target="_blank"><img src='images/paper8_thumb.jpg' alt="SemEval System" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

**UIUC_BioNLP at SemEval-2021 Task 11: A Cascade of Neural Models for Structuring Scholarly NLP Contributions** 🏆 *Best System Paper (1/175)*

**Haoyang Liu**, Janina Sarol, Halil Kilicoglu

*The 15th International Workshop on Semantic Evaluation (SemEval)*, 2021

A cascade of neural models combining BERT-based classifiers with rule-based systems for extracting structured contributions from NLP papers. Ranked first overall across all evaluation phases.

[[Paper]](https://aclanthology.org/2021.semeval-1.45/) [[arXiv]](https://arxiv.org/abs/2105.05435) [[Code]](https://github.com/Liu-Hy/nlp-contrib-graph)
</div>
</div>


# Education
- *2023 - Present*, Ph.D. in Informatics, University of Illinois Urbana-Champaign


# Contact
Feel free to reach out via email at hl57@illinois.edu.
