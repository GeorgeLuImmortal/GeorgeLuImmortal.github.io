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

I work at ByteDance <img src='./images/tiktok.png' style='width: 6em;'> as a AI researcher now in Shanghai, China. 

I am now working on NLP, multi-modality, LLM-related foundational research, particular in LLM speedup, KIE and document AI. If you are seeking any form of **academic cooperation**, please feel free to email me at [lujinghui@bytedance.com](mailto:lujinghuii@bytedance.com). We are hiring interns!

I graduated with a Bachelor's degree in Software Engineering from [Xiamen University (厦门大学)](https://www.xmu.edu.cn/) and earned a Master's degree from the School of Computer Science at [University College Dublin (都柏林大学)](https://www.ucd.ie/), where I was advised by [Prof. Mark Keane](https://people.ucd.ie/mark.keane), focusing on natural language processing. Then, I completed my PhD at University College Dublin under the supervision of [Prof. Brian Mac Namee](https://people.ucd.ie/brian.macnamee), focusing on interdisciplinary methods for Deep Learning, NLP and Human-in-the-loop. I also collaborate with [Dr. Irene Li](https://ireneli.eu/) from [Li Lab](https://www.li-lab.me/home), the University of Tokyo closely.

My research interest includes NLP, multi-modality, document AI and human-in-the-loop. I have published 20+ papers <a href='https://scholar.google.com/citations?hl=en&user=ZzK_UdYAAAAJ'><img src="https://img.shields.io/endpoint?logo=Google%20Scholar&url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2FGeorgeLuImmortal%2FGeorgeLuImmortal.github.io@google-scholar-stats%2Fgs_data_shieldsio.json&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> at the top international AI and NLP conferences such as NeurIPS, ACL, NAACL, AAAI, COLING. 


# 🔥 News
- *2024.10*: &nbsp;🎉 One first-author paper has been accepted to NeurIPS 2024.
- *2024.07*: &nbsp;🎉 We released LayTextLLM, interleaving layout and text information for LLM, achieving SOTA performance across multiple document AI benchmarks \| [**Project**](https://github.com/LayTextLLM/LayTextLLM) \| [![](https://img.shields.io/github/stars/LayTextLLM/LayTextLLM?style=social&label=Code+Stars)](https://github.com/LayTextLLM/LayTextLLM) \| [![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue?label=Model)](https://huggingface.co/LayTextLLM).
- *2024.05*: &nbsp;🎉 We released MTVQA, which is the first text-centric multilingual multimodality benchmark for LLMs \| [**Project**](https://bytedance.github.io/MTVQA/) \| [![](https://img.shields.io/github/stars/bytedance/MTVQA?style=social&label=Code+Stars)](https://github.com/bytedance/MTVQA) \| [![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue?label=Data)](https://huggingface.co/datasets/ByteDance/MTVQA).
- *2024.05*: &nbsp;🎉 One paper has been accepted to ACL 2024 findings. 
- *2024.03*: &nbsp;🎉 One paper has been accepted to NAACL 2024.
- *2024.02*: &nbsp;🎉 One co-first author paper has been accepted to COLING-LREC 2024.
- *2023.06*: &nbsp;🎉 One first-author paper has been accepted to AAAI 2023. 
- *2023.05*: &nbsp;🎉 One first-author paper has been accepted to ACL 2023.
- *2023.05*: &nbsp;🎉 One paper has been accepted to ACL 2023 findings.
- *2022.03*: &nbsp;🎉 One first-author paper has been accepted to ACL 2022.
- *2021.07*: &nbsp;🎉 One first-author paper has been accepted to ICML 2021 Workshop.

# 📝 Selected Publications 

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2022</div></div></div> -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2023</div><img src='images/acl_22_fig.png' height="200"></div></div>
<div class='paper-box-text' markdown="1">

**PUnifiedNER: a prompting-based unified NER system for diverse datasets**

**Jinghui Lu** , Rui Zhao, Brian Mac Namee, Fei Tan U+2709

We present a novel rational-centric framework with human-in-the-loop – Rationales-centric Double-robustness Learning (RDL) – to boost model out-of-distribution performance in few-shot learning scenarios. By using static semi-factual generation and dynamic human-intervened correction, RDL, acting like a sensible “inductive bias”, exploits rationales (i.e. phrases that cause the prediction), human interventions and semi-factual augmentations to decouple spurious associations and bias models towards generally applicable underlying distributions, which enables fast and accurate generalisation. Experimental results show that RDL leads to significant prediction benefits on both in-distribution and out-of-distribution tests, especially for few-shot learning scenarios, compared to many state-of-the-art benchmarks.

[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/26564/26336) [Code](https://github.com/GeorgeLuImmortal/PUnifiedNER)

</div>
</div>

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2022</div></div></div> -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2022</div><img src='images/acl_22_fig.png' height="200"></div></div>
<div class='paper-box-text' markdown="1">

**A Rationale-Centric Framework for Human-in-the-loop Machine Learning**

**Jinghui Lu** *, Linyi Yang *, Brian Mac Namee, Yue Zhang

We present a novel rational-centric framework with human-in-the-loop – Rationales-centric Double-robustness Learning (RDL) – to boost model out-of-distribution performance in few-shot learning scenarios. By using static semi-factual generation and dynamic human-intervened correction, RDL, acting like a sensible “inductive bias”, exploits rationales (i.e. phrases that cause the prediction), human interventions and semi-factual augmentations to decouple spurious associations and bias models towards generally applicable underlying distributions, which enables fast and accurate generalisation. Experimental results show that RDL leads to significant prediction benefits on both in-distribution and out-of-distribution tests, especially for few-shot learning scenarios, compared to many state-of-the-art benchmarks.

[Paper](https://aclanthology.org/2022.acl-long.481/) [Code](https://github.com/GeorgeLuImmortal/RDL-Rationales-centric-Double-robustness-Learning)

</div>
</div>

# 🎖 Honors and Awards
- *2024.06* Award for High-Level Overseas Talents, Shanghai, China
- *2023.01* Outstanding Project Annual, SCG, SenseTime Group Ltd. China
- *2016.09* Walsh Fellowship Award, Ireland.
- *2015.09* Graduate Global Scholarship (<0.5\%), University College Dublin, Ireland

# 📖 Educations
- *2016.09 - 2021.01*, Phd, University College Dublin, Ireland.
- *2015.09 - 2016.06*, Master, University College Dublin, Ireland.
- *2011.09 - 2015.06*, Undergraudate, Xiamen University, China.
- *2008.09 - 2011.06*, Fuzhou No. 1 Middle School, China.

# 💬 Invited Talks
- *2023.01*, ChatGPT的前世今生与未来 (建信信托2023浪潮之巅沙龙, Beijing, China)
- *2022.11*, Diffusion Model and its Applications (SuzumuraLab tutorial, the Univeristy of Tokyo), [Slide](https://ireneli.eu/wp-content/uploads/2022/11/ddpm_lab.pdf), [Post](https://www.linkedin.com/posts/irenelizihui_ddpmlabpdf-activity-7002228308272717824-KWak?utm_source=share&utm_medium=member_desktop)

# 💻 Community Service
- *2020 - Now*, serve as a review at ACL, AAAI, ICLR, NAACL, COLING, EMNLP, NeurIPS, etc.
