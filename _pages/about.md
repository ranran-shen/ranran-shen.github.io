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

Hi:wave:, I am Zhaoyi Li, a computer science PhD student under the collaboration programm of [University of Science and Technology of China](https://en.ustc.edu.cn/) ([School of Computer Science and Technology](https://en.cs.ustc.edu.cn/main.htm) and [State Key Laboratory of Cognitive Intelligence](https://cogskl.iflytek.com/), adviced by Prof.[Defu Lian](https://scholar.google.com.hk/citations?user=QW0ad4sAAAAJ&hl=en)) and [City University of Hong Kong](https://www.cityu.edu.hk/) ([Department of Computer Science](https://www.cs.cityu.edu.hk/), co-adviced by Prof.[Ying Wei](https://wei-ying.net/) and Prof.[Linqi Song](https://sites.google.com/site/aisquaredlab/about-us/linqi)).
The most fortunate thing for my early PhD life is that I met up with my brilliant professors!
Previously, I got my Bachelor degree in Computer Science and Technology from University of Science and Technology of China in 2022, under the supervision of Prof.[Cheng Li](http://staff.ustc.edu.cn/~chengli7/).

My research interest includes machine learning and natural language processing. Specifically, I work on making human beings and neural network systems better understand each other (i.e., generalization and interpretability). I currently focus on investigating the compositionality of language models from the perspectives of generalization, reasoning pattern, implicit structure and so on, which is about the mechanism that language models decompose complex questions and concepts into primitive ones and re-compose them step-by-step to grasp the complex semantic meaning. Recently the emerging term ["System-1 thinking v.s. System-2 thinking"](https://thedecisionlab.com/reference-guide/philosophy/system-1-and-system-2-thinking) also closely relates to my projects. I would love to discuss on related topics should anyone is interested (always feel free to drop me an email: lizhaoyi777\[AT\]mail.ustc.edu.cn)!


# 🔥 News
- *2024.09*: &nbsp;🎉🎉 One paper was accepted by EMNLP'2024 (main conference). 
- *2024.05*: &nbsp;🎉🎉 Two papers was accepted by ACL'2024 (1$\times$main conference and 1$\times$findings). 
- *2023.05*: &nbsp;🎉🎉 One paper was accepted by ACL'2023 (main conference). 

# 📝 Publications 
($\*$ indicates the co-first authorship)
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2024</div><img src='images/emnlp2024_mt.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
<ins>Mitigating the Language Mismatch and Repetition Issues in LLM-based Machine Translation via Model Editing</ins> (**EMNLP'2024**)

Weichuan Wang$^\*$, **Zhaoyi Li**$^\*$, Defu Lian, Chen Ma, Linqi Song and Ying Wei

[**Paper**] [**Code**] 
- We investigate two common types of issues, Language Mismatch and Repetition, in LLM-based machine translation systems. We mitigate such issues to some extent by the refined model editing methods without hurting the general abilities of LLMs.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2024 Findings</div><img src='images/acl2024_new.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
<ins>Understanding and Patching Compositional Reasoning in LLMs</ins> (**ACL'2024 Findings**)

**Zhaoyi Li**, Gangwei Jiang, Hong Xie, Linqi Song, Defu Lian and Ying Wei

[**Paper**](https://arxiv.org/abs/2402.14328) [**Code**](https://github.com/Zhaoyi-Li21/creme) [**Blog(in Chinese)**](https://zhuanlan.zhihu.com/p/684626522)
- We interpret the internal mechanism of compositional step-by-step reasoning on multi-hop factual knowledge inside large language models and propose a light-weight method based on model editing to patch their compositional reasoning errors.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2024</div><img src='images/acl2024a.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<ins>Benchmarking and Improving Compositional Generalization of Multi-aspect Controllable Text Generation</ins> (**ACL'2024**)

Tianqi Zhong$^\*$, **Zhaoyi Li**$^\*$, Quan Wang, Linqi Song, Ying Wei, Defu Lian and Zhendong Mao

[**Paper**](https://arxiv.org/pdf/2404.04232) [**Code**](https://github.com/tqzhong/CG4MCTG)
- We propose CompMCTG, systematically unveiling the shortcoming of current multi-aspect controllable text generation methods on compositional generalization. Besides, we propose MetaMCTG, a meta-learning based training framework to improve the compositional generalization performance of current methods.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2023 Oral</div><img src='images/acl2023.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<ins>Learning to Substitute Spans towards Improving Compositional Generalization</ins> (**ACL'2023 Oral**)

**Zhaoyi Li**, Ying Wei and Defu Lian

[**Paper**](https://aclanthology.org/2023.acl-long.157/) [**Code**](https://github.com/Zhaoyi-Li21/Compgen_l2s2)
- We propose L2S2, a adversarial learning based text data augmentation scheme to improve the compositional generalization performance of neural sequence models (including LSTMs, Transformers and Pre-trained LMs). 
</div>
</div>

# 🎖 Honors and Awards
- *2023.10*, National Scholarship.
- *2022 ~ 2023*, First Prize, *USTC Graduate Student Academic Scholarship*.
- *2022.06*, Honored as *The Outstanding Bachelor Graduate of CSU*.
- *2022.06*, Honored as *The Outstanding Bachelor Graduate of Hunan province*.
- *2021.10*, National Scholarship (Undergraduate).
- *2019 ~ 2021*, Honored as *The Outstanding Student of School of Computer Science and Engineering, CSU*.
- *2020 ~ 2021*, First Prize, *CSU Undergraduate Student Academic Scholarship*.
- *2019.10*, Second Prize, *CSU Undergraduate Student Academic Scholarship*.
   
# 📖 Educations 
- *2022.09 - now*, Master, School of Computer Science and Technology, University of Science and Technology of China. 
- *2018.09 - 2022.06*, Undergraduate, School of Computer Science and Engineering, Central South University. 

# 💻 Internships
- *2024.04 - 2024.08*, Tencent, Shenzhen.

# 🎖 Services
- Teaching Assistant:
  - USTC, Algorithm Design and Analysis [COMP6001P03], 2023 Fall
