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

Hi there! I am Ranran Shen (申冉冉), a Ph.D. student in Computer Science at [University of Science and Technology of China (USTC)](https://en.ustc.edu.cn/). I feel incredibly fortunate to be advised by Prof. [Pan Peng](http://staff.ustc.edu.cn/~ppeng/), whose guidance has been instrumental in shaping my academic journey.
Previously, I got my Bachelor's degree in Computer Science and Technology from [Central South University (CSU)](https://en.csu.edu.cn/) in 2022, where I was advised by Prof. [Ying Zhao](https://faculty.csu.edu.cn/zhaoying).

My research interests lie broadly in sublinear-time algorithms and graph algorithms. Specifically, I am currently focusing on sublinear-time clustering algorithms on graphs, though I am still in the process of forming a more defined understanding of my research direction.

If you are interested in TCS, please refer to the [CS Theory Group at USTC](https://tcs.ustc.edu.cn/main.htm) webpage for more information. If you’d like to discuss my research or have any questions, please feel free to email me at: ranranshen@mail.ustc.edu.cn.


# 🔥 News
- *2026.01*: &nbsp;🎉🎉 One paper is accepted by ICLR'2026 (main conference) and many thanks to my co-authors!📝
- *2024.04*: &nbsp;🎉🎉 Thrilled to start an internship at Tencent, focusing on GUI agent.💻
- *2023.12*: &nbsp;🎉🎉 Incredibly excited to attend the NeurIPS'2023 conference (hosted in New Orleans, Louisiana, USA) and present my poster.✈️
- *2023.10*: &nbsp;🎉🎉 I'm honored to receive the National Scholarship!🏆
- *2023.09*: &nbsp;🎉🎉 One paper is accepted by NeurIPS'2023 (main conference)!📝

# 📝 Publications 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/ICLR2026.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
<ins>Sublinear Spectral Clustering Oracle with Little Memory</ins> (**ICLR'2026**)

**Ranran Shen**, Xiaoyi Zhu, [Pan Peng](http://staff.ustc.edu.cn/~ppeng/), [Zengfeng Huang](https://zengfenghuang.github.io/)

**Paper** and **Poster** will be updated soon.
- We study the problem of designing sublinear spectral clustering oracles for well-clusterable graphs. A major limitation of existing oracles is that constructing $\mathcal{D}$ requires $\Omega(\sqrt{n})$ memory, which becomes a bottleneck for massive graphs and memory-limited settings. In this paper, we break this barrier and establish a memory-time trade-off for sublinear spectral clustering oracles.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2023</div><img src='images/neurips2023_new.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
<ins>A Sublinear-Time Spectral Clustering Oracle with Improved Preprocessing Time</ins> (**NeurIPS'2023**)

**Ranran Shen**, [Pan Peng](http://staff.ustc.edu.cn/~ppeng/)

[**Paper**](https://arxiv.org/pdf/2310.17878)｜[**Slides (5 min)**](../docs/NeurIPS2023-slides-5-min.pdf)｜[**Slides**](../docs/NeurIPS2023-slides-full-version.pdf)｜[**Poster**](https://neurips.cc/media/PosterPDFs/NeurIPS%202023/72688.png?t=1701588568.181395)
- We address the problem of designing a sublinear-time spectral clustering oracle for graphs that exhibit strong clusterability. Previous oracles have relied on either a $\textrm{poly}(k)\cdot\log n$ gap between inner and outer conductances or exponential (in $k/\varepsilon$) preprocessing time. Our algorithm relaxes these assumptions, albeit at the cost of a slightly higher misclassification ratio.
</div>
</div>


# 📖 Education
- *2022.09 ~ present*, Ph.D. student, [School of Computer Science and Technology](https://en.cs.ustc.edu.cn/main.htm), University of Science and Technology of China (USTC), Hefei.
  - in successive master-doctor program.
- *2018.09 ~ 2022.06*, Undergraduate, [School of Computer Science and Engineering](https://cse.csu.edu.cn/), Central South University (CSU), Changsha. 


# 💻 Internships
- *2024.04 ~ 2024.08*, [Tencent](https://www.tencent.com/en-us/) <img src='../images/tencent_logo.png' style='width: 6em;'>, Shenzhen.


# 🏆 Honors and Awards
- *2026.03*, ICLR 2026 Travel Grant.
- *2023.10*, National Scholarship (**Top 2%**)🌷.
- *2022 ~ 2025*, First Prize, *USTC Graduate Student Academic Scholarship*.
- *2022.06*, Honored as *The Outstanding Bachelor Graduate of Hunan Province* (**Top 3%**).
- *2022.06*, Honored as *The Outstanding Bachelor Graduate of CSU* (**Top 15%**).
- *2021.10*, National Scholarship (Undergraduate, **Top 2%**)🌷.
- *2019 ~ 2021*, Honored as *The Outstanding Student of School of Computer Science and Engineering, CSU*.
- *2020 ~ 2021*, First Prize, *CSU Undergraduate Student Academic Scholarship*.
- *2019.10*, Second Prize, *CSU Undergraduate Student Academic Scholarship*.
   

# 🎖 Services
- Invited Reviewer:
  - ICLR 2026, ICML 2026.
- Teaching Assistant:
  - Spring 2025: [Algorithms for Big Data](https://icourse.club/course/21471/) (Undergraduate, USTC). Instructor: Prof. [Pan Peng](http://staff.ustc.edu.cn/~ppeng/).
  - Fall 2023: Design and Analysis of Algorithms (Graduate, USTC). Instructors: Prof. [Pan Peng](http://staff.ustc.edu.cn/~ppeng/) and Prof. [Xiaohua Xu](http://staff.ustc.edu.cn/~xiaohuaxu/).


# 🦕 Special Links
- Here is the link to the homepage of my boyfriend: [Zhaoyi Li](https://zhaoyi-li21.github.io/).
