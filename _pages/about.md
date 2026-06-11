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

# 🎓 About me
I am now a PhD student at the Hong Kong University of Science and Technology (Guangzhou), where I am honored to be supervised by [Prof. Lei Chen](https://facultyprofiles.hkust-gz.edu.cn/faculty-personal-page/CHEN-Lei/leichen). My current research interests include:
- Agentic System
- Multi-modal RAG
- Unsupervised Machine Learning


<!-- ➡️ Download my [Resumé](./uploads/Jiang's CV.pdf) -->

### 🔺*Last Update: 2026/06/11*

# 🔥 News
- *2025.09*: &nbsp;🎉🎉 I became a PhD student at HKUST(GZ).
- *2025.08*: &nbsp;🎉🎉 I finished my research assistantship at HKUST(GZ).
<!-- - *2025.05*: &nbsp;🎉🎉 One paper got accepted by ACL 2025 (Industry Track). -->
- *2024.08*: &nbsp;🎉🎉 I finished my research assistantship at SIAT-CAS.

# 📑 Publications 

<!--paperDaLC-->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/DaLC.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DaLC: Difficulty-aware Label Completion for Crowdsourcing Truth Inference](https://github.com/JunjieChiang/DaLC) (Under Review)

**Junjie Jiang**, Jiachuan Wang*, Yongqi Zhang, Jiake Ge, Shuangyin Li, Lei Chen
- Proposes DaLC, a Difficulty-aware Label Completion framework for crowdsourcing truth inference
- Introduces a Neighbor Consistency Score (NCS) to quantify object inference difficulty from neighborhood consistency, splitting objects into easy, ambiguous, and hard subsets
- Estimates worker reliability in a difficulty-conditioned manner and completes the sparse matrix via a heterogeneous worker-object graph supervised by difficulty-aware soft targets under a joint training objective
- Experiments on 6 real-world and 34 simulated datasets show DaLC generalizes across aggregators and achieves the best downstream truth-inference performance

[**Code Here**](https://github.com/JunjieChiang/DaLC)

Keywords: Crowdsourcing, Truth Inference, Label Completion, Worker Reliability, Graph Neural Network
</div>
</div>

<!--paper0-->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2025 (Industry Track)</div><img src='images/archidocgen.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ArchiDocGen: Multi-Agent Framework for Expository Document Generation in the Architectural Industry](https://aclanthology.org/2025.acl-industry.43/)

**Junjie Jiang**, Haodong Wu, Yongqi Zhang, Songyue Guo, Bingcen Liu, Caleb Chen Cao, Ruizhe Shao, Chao Guan, Peng Xu, Lei Chen*
- A multi-agent framework that automates method-statement (expository document) generation in the architectural industry
- Decomposes the task into outline generation, section-based content generation, and polishing, each handled by a specialized agent
- A section-based retriever and a section-based chain-of-thought (SeCoT) scheme inject domain knowledge and iterative reasoning
- Achieves a 4.38 ContentScore and is deployed as a web application with industry partners

Keywords: Multi-Agent, Retrieval-Augmented Generation, Document Generation, Large Language Model, Architectural Industry
</div>
</div>

<!--paper3-->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Expert Systems With Applications</div><img src='images/ESWA.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A compatible detector based on improved YOLOv5 for hydropower device detection in AR inspection system](https://www.sciencedirect.com/science/article/abs/pii/S0957417423005675)

**Junjie Jiang**, Zhile Yang, Chengke Wu, Yuanjun Guo, Meng Yang, Wei Feng*
- A Compatible detector is proposed for device detection in AR inspection system
- Computation cost is improved by a lightweight backbone network
- A coordinate-based attention module is designed for effective feature fusion
- Optimizing hyperparameters of the new architecture to make the detector robust

[**Code Here**](https://codeocean.com/capsule/2938777/tree/v1) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

Keywords: Object Detection, Augmented Reality, Genetic Algorithm, Power Grid 
</div>
</div>

<!--paper4-->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Advanced Engineering Informatics</div><img src='images/ADEI_2.jpg' alt="sym" width="110%" height="150%"></div></div>
<div class='paper-box-text' markdown="1">

[A teacher–student deep learning strategy for extreme low resolution unsafe action recognition in construction projects](https://www.sciencedirect.com/science/article/pii/S1474034623004226)

Meng Yang, Chengke Wu, Yuanjun Guo, Yong He, Rui Jiang, **Junjie Jiang**, Zhile Yang*
- A teacher-student deep learning framework is proposed for identifying unsafe behaviours
- The useful feature is captured from extremely low resolution video
- Knowledge learning model and similarity loss function are designed for better training of student network

Keywords: Action Recognition, Knowledge Distillation, Low Resolution, Construction Safety 
</div>
</div>

## Selected Patents
- Yang, Z., **Jiang, J.**, Guo, Y., Liu, X., Wu, C. Method, System, and Related Equipment for Battery Surface Defect Detection Based on Machine Vision. WIPO (PCT) Patent, WO2023226357A1, [publication](./images/PCT1.png)
- Yang, Z., **Jiang, J.**, Liu, X., Guo, Y., Wu, C. A Real-time Optimization Control Method for Charging and Discharging States of a Hybrid Energy Storage System(一种混合储能系统充放电状态实时优化控制方法). National Invention Patent, CN115313447A, [authorized](./images/patent_2.png)
- Guo, Y., **Jiang, J.**, Wu, C., Yang, ., Hu, T. Method, System, and Related Equipment for Defect Detection Based on Battery Surface Images(基于电池表面图像的缺陷检测方法、系统及相关设备). National Invention Patent, CN115272330A, [authorized](./images/patent_3.png)
- Yang, Z., **Jiang, J.**, Guo, Y., Liu, X., Wu, C. Method, System, and Related Equipment for Battery Surface Defect Detection Based on Machine Vision(基于机器视觉的电池表面缺陷检测方法、系统及相关设备). National Invention Patent, CN114972258B, [authorized](./images/patent_1.png)

# 🛠 Projects

<!--project-archidocgen-->
<div class='project-box'>
<div class='project-box-image'><img src='projects/archidocgen.gif' alt="ArchiDocGen demo" width="100%"></div>
<div class='project-box-text' markdown="1">

**ArchiDocGen** — Multi-Agent Expository Document Generation for the Architectural Industry

A deployed web application that automatically drafts construction *method statements* end-to-end: outline generation, section-based content generation with retrieval-augmented reasoning, and final polishing — each handled by a specialized agent. Built and deployed with our industry partner [China State Construction Engineering (Hong Kong) Limited](https://www.csci.com.hk/), and presented at ACL 2025 (Industry Track).

[**Paper**](https://aclanthology.org/2025.acl-industry.43/)

</div>
</div>

# 🎖 Honors and Awards
- *2024.01* SIAT President's Scholarship-Excellent Award (top 5%), Shenzhen Institute of Advanced Technology, CAS
- *2024.01* SIAT Outstanding Contribution Award-2023
- *2024.01* Director's Innovation Award-Outstanding Graduate Student, Shenzhen Institute of Advanced Integrated Technology, CAS-CUHK(中国科学院香港中文大学深圳先进集成技术研究所)
- *2022.12* The 2022 SEIC Outstanding Contribution Award, Shenzhen Institute of Advanced Technology, CAS
- *2022.06* Excellent Undergraduate Thesis of Shenyang Ligong University, SYLU
- *2019.11* Third Prize in Robot Competition of the School of Mechanical Engineering, SYLU

# 📖 Educations
- *2025.09 - Present*, PhD Student, Data Science and Analytics, HKUST(GZ)
- *2022.05 - 2024.08*, Visiting Student, SIAT, Chinese Academy of Sciences
- *2018.06 - 2022.09*, Undergraduate, Robot Engineering, SYLU

<!-- # 💬 Invited Talks
- *2021.06*, Nanjing Normal University 
- *2021.03*, Nanjing Normal University
-->

# 💻 Work Experience
- *2025.03 - 2025.08*, Research Assistant, HKUST(GZ).
- *2022.05 - 2024.08*, Research Assistant, SIAT, Chinese Academy of Sciences.