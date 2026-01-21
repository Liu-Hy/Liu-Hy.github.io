---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>

I am Haoyang Liu<a href="#name-note" style="text-decoration: none; color: inherit;"><sup>1</sup></a>, a PhD student in Informatics at the [School of Information Sciences](https://ischool.illinois.edu/), University of Illinois Urbana-Champaign. I am fortunate to be advised by Prof. [Bertram Ludäscher](https://scholar.google.com/citations?user=nYx9xasAAAAJ&hl=en). Prior to that, I had the opportunity to work with Prof. [Haohan Wang](https://haohanwang.github.io/) on trustworthy ML, Prof. [Halil Kilicoglu](https://kilicogluh.github.io/) on biomedical NLP, and interned at BNRist, Tsinghua University advised by Prof. [Chunxiao Xing](https://scholar.google.com/citations?user=8uj6pAsAAAAJ&hl=en).

My research aims to develop **trustworthy machine learning** methods and systems. I have studied ways to evaluate and improve model robustness ([ICLR 2024](https://arxiv.org/abs/2308.10632), [CPAL 2025 Oral](https://arxiv.org/abs/2403.10476)), dataset distillation for more compute- and data-efficient learning ([ICCV 2025](https://arxiv.org/abs/2311.18531)) that also improves robustness ([AAAI 2025](https://arxiv.org/abs/2403.10045)), and LLM agents for robust automation of biomedical data analysis workflows ([MLCB 2025 Oral](https://arxiv.org/abs/2406.15341)). Currently, I am interested in combining **formal methods** with **LLM agents** for trustworthy reasoning and automation, with applications in biomedical and legal domains.

<span class='anchor' id='publications'></span>
# Selected Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2025</div><a href="images/paper1_full.png" target="_blank"><img src='images/paper1_thumb.jpg' alt="GenoMAS" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

**GenoMAS: A Multi-Agent Framework for Scientific Discovery via Code-Driven Gene Expression Analysis**

**Haoyang Liu**, Yijiang Li, Haohan Wang

*arXiv preprint*, 2025

A multi-agent framework that combines workflow controllability with agentic autonomy for automated gene expression analysis. Features a guided-planning mechanism that enables agents to dynamically advance, revise, or backtrack while maintaining logical coherence.

[[Website]](https://liu-hy.github.io/GenoMAS/) [[Paper]](https://arxiv.org/abs/2507.21035) [[Code]](https://github.com/Liu-Hy/GenoMAS)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><a href="images/paper2_full.png" target="_blank"><img src='images/paper2_thumb.jpg' alt="WMDD" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

**Dataset Distillation via the Wasserstein Metric**

**Haoyang Liu**, Yijiang Li, Tiancheng Xing, Peiran Wang, Vibhu Dalal, Luwei Li, Jingrui He, Haohan Wang

*IEEE/CVF International Conference on Computer Vision (ICCV)*, 2025

Leverages optimal transport theory for dataset distillation, using Wasserstein barycenter to preserve geometric characteristics of the original data distribution. Achieves consistent state-of-the-art performance across multiple high-resolution benchmarks.

[[Website]](https://liu-hy.github.io/WMDD/) [[Paper]](https://arxiv.org/abs/2311.18531) [[Code]](https://github.com/Liu-Hy/WMDD)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MLCB 2025</div><a href="images/paper3_full.jpg" target="_blank"><img src='images/paper3_thumb.jpg' alt="GenoTEX" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

**GenoTEX: An LLM Agent Benchmark for Automated Gene Expression Data Analysis**

**Haoyang Liu**, Shuyu Chen, Ye Zhang, Haohan Wang

*The 20th Machine Learning in Computational Biology Conference (MLCB)*, 2025 <br> 🎖️ *Oral (14.4%)*

A benchmark for evaluating LLM agents on automated gene expression analysis, featuring 913 real-world datasets with realistic complexities covering 132 human traits.

[[Website]](https://liu-hy.github.io/GenoTEX/) [[Paper]](https://arxiv.org/abs/2406.15341) [[Code]](https://github.com/Liu-Hy/GenoTEX) [[Dataset]](https://huggingface.co/datasets/Liu-Hy/GenoTEX)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CPAL 2025</div><a href="images/paper4_full.png" target="_blank"><img src='images/paper4_thumb.jpg' alt="NAF" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

**Approximate Nullspace Augmented Finetuning for Robust Vision Transformers**

**Haoyang Liu**, Aditya Singh, Yijiang Li, Haohan Wang

*The 2nd Conference on Parsimony and Learning (CPAL)*, 2025 🎖️ *Oral (12.7%)*

Generalizes the nullspace concept from linear layers to non-linear ViT encoder blocks, enhancing both adversarial and natural robustness while maintaining clean accuracy.

[[Website]](https://liu-hy.github.io/NS-ViT/) [[Paper]](https://arxiv.org/abs/2403.10476) [[Code]](https://github.com/Liu-Hy/ns-vit)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025</div><a href="images/paper5_full.png" target="_blank"><img src='images/paper5_thumb.jpg' alt="GUARD" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

**Towards Adversarially Robust Dataset Distillation by Curvature Regularization**

Eric Xue, Yijiang Li, **Haoyang Liu**, Peiran Wang, Yifan Shen, Haohan Wang

*The 39th AAAI Conference on Artificial Intelligence (AAAI)*, 2025

Embeds adversarial robustness into distilled datasets via curvature regularization. Minimizes loss landscape curvature during distillation, reducing adversarial vulnerability with significantly less overhead than adversarial training.

[[Website]](https://yumozi.github.io/GUARD/) [[Paper]](https://arxiv.org/abs/2403.10045) [[Code]](https://github.com/yumozi/GUARD)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2024</div><a href="images/paper6_full.png" target="_blank"><img src='images/paper6_thumb.jpg' alt="FMOR" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

**Foundation Model-oriented Robustness: Robust Image Model Evaluation with Pretrained Models**

Peiyan Zhang, **Haoyang Liu**, Chaozhuo Li, Xing Xie, Sunghun Kim, Haohan Wang

*The 12th International Conference on Learning Representations (ICLR)*, 2024

A dynamic robustness evaluation protocol using foundation models as surrogate oracles, enabling evaluation beyond fixed benchmarks through semantically bounded perturbations.

[[Paper]](https://arxiv.org/abs/2308.10632)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2023</div><a href="images/paper7_full.png" target="_blank"><img src='images/paper7_thumb.jpg' alt="Trustworthy ML Survey" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

**Towards Trustworthy and Aligned Machine Learning: A Data-centric Survey with Causality Perspectives**

**Haoyang Liu**, Maheep Chaudhary, Haohan Wang

*arXiv preprint*, 2023

A data-centric survey on trustworthy ML covering robustness, security, interpretability, and fairness, unified through Pearl's causal hierarchy.

[[Website]](https://trustworthyartificialintelligence.github.io/papers/trustworthyMLsurvey.html) [[Paper]](https://arxiv.org/abs/2307.16851)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SemEval 2021</div><a href="images/paper8_full.png" target="_blank"><img src='images/paper8_thumb.jpg' alt="SemEval System" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

**UIUC_BioNLP at SemEval-2021 Task 11: A Cascade of Neural Models for Structuring Scholarly NLP Contributions**

**Haoyang Liu**, Janina Sarol, Halil Kilicoglu

*The 15th International Workshop on Semantic Evaluation (SemEval)*, 2021 <br> 🏆 *Best System Paper (1/175)*

A neuro-symbolic approach combining BERT-based classifiers with rule-based systems for extracting structured contributions from NLP papers. Ranked first overall across all evaluation phases.

[[Paper]](https://arxiv.org/abs/2105.05435) [[Code]](https://github.com/Liu-Hy/nlp-contrib-graph)
</div>
</div>


<span class='anchor' id='honors-and-awards'></span>
# Honors and Awards
- *2022*, [**List of Teachers Ranked as Excellent**](https://ischool.illinois.edu/news-events/news/2023/03/ischool-instructors-ranked-excellent), University of Illinois Urbana-Champaign
- *2021*, [**Best System Paper Award**](https://semeval.github.io/SemEval2021/awards) (1st place out of 175 submissions), SemEval 2021

<span class='anchor' id='education'></span>
# Education
- *2020.06 - Present*, **Ph.D. in Informatics**, University of Illinois Urbana-Champaign, USA
- *2020.01 - 2020.05*, **Visiting Student in Computer Science**, Illinois Institute of Technology, USA
- *2016.09 - 2020.06*, **B.S. in Telecommunication Engineering**, Beijing University of Posts and Telecommunications, China

<span class='anchor' id='invited-talks'></span>
# Invited Talks
- *2025.03*, **Approximate Nullspace Augmented Finetuning for Robust Vision Transformers**, [CPAL 2025](https://2025.cpal.cc/orals/) Highlight Talk, Stanford University
- *2021.11*, **Information Extraction from NLP Literature**, Research Showcase, UIUC School of Information Sciences
- *2021.08*, **UIUC_BioNLP System at SemEval-2021**, 15th International Workshop on Semantic Evaluation (Virtual)

<span class='anchor' id='teaching-and-services'></span>
# Teaching and Services

**Teaching**
- *FA22*, **Instructor of Record**, IS 203: Analytical Foundations for Information Problems, UIUC
- *SP24*, **Teaching Assistant**, IS 597 TML: Trustworthy Machine Learning, UIUC
- *FA23*, **Teaching Assistant**, IS 507: Data, Statistical Models, and Information, UIUC

**Academic Services**
- **Conference Reviewer**: ICML (2023-2024), NeurIPS (2024), ICLR (2024-2026), CVPR (2025-2026)
- **Program Committee Member**: AAAI 2026, KDD 2026 D&B Track

<span class='anchor' id='internships'></span>
# Internships
- *2019.03 - 2019.09*, **Research Intern**, Beijing National Research Center for Information Science and Technology (BNRist), Tsinghua University, Beijing, China
  - Advisor: Prof. [Chunxiao Xing](https://scholar.google.com/citations?user=8uj6pAsAAAAJ&hl=en)
  - Developed automated system to construct medical knowledge graphs from electronic health records
  - Built multimodal neural network for diabetes risk prediction from clinical notes and tabular data

---

<p id="name-note" style="font-size: 0.9em; color: #666;"><sup>1</sup> Written in Chinese as 刘昊洋. Pronounced as <em>How-yahng Lee-oh</em>.</p>
