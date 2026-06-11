---
layout: home
permalink: /
title: ""
redirect_from:
  - /about/
  - /about.html
---

# About
I am a PhD student at the Hong Kong University of Science and Technology (Guangzhou), advised by [Prof. Lei Chen](https://facultyprofiles.hkust-gz.edu.cn/faculty-personal-page/CHEN-Lei/leichen). My work sits at the intersection of large language models and data systems — building agentic pipelines and multimodal retrieval that turn messy, knowledge-intensive sources into reliable, structured output. Before my PhD, I spent three years as a research assistant across HKUST(GZ) and SIAT-CAS, working on document intelligence and computer vision for industrial settings.

- Agentic System
- Multi-modal RAG
- Unsupervised Machine Learning

<p class="last-update">Last updated · {{ site.time | date: "%Y-%m-%d" }}</p>

# News
- *2025.09* I became a PhD student at HKUST(GZ).
- *2025.08* I finished my research assistantship at HKUST(GZ).
- *2024.08* I finished my research assistantship at SIAT-CAS.

# Publications

<!--paperDaLC-->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/DaLC.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DaLC: Difficulty-aware Label Completion for Crowdsourcing Truth Inference](https://github.com/JunjieChiang/DaLC) (Under Review)

**Junjie Jiang**, Jiachuan Wang\*, Yongqi Zhang, Jiake Ge, Shuangyin Li, Lei Chen
- Proposes DaLC, a Difficulty-aware Label Completion framework for crowdsourcing truth inference
- Introduces a Neighbor Consistency Score (NCS) to quantify object inference difficulty from neighborhood consistency, splitting objects into easy, ambiguous, and hard subsets
- Estimates worker reliability in a difficulty-conditioned manner and completes the sparse matrix via a heterogeneous worker-object graph supervised by difficulty-aware soft targets under a joint training objective
- Experiments on 6 real-world and 34 simulated datasets show DaLC generalizes across aggregators and achieves the best downstream truth-inference performance

[**Code**](https://github.com/JunjieChiang/DaLC)

Keywords: Crowdsourcing, Truth Inference, Label Completion, Worker Reliability, Graph Neural Network
</div>
</div>

<!--paper0-->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2025 (Industry Track)</div><img src='images/archidocgen.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ArchiDocGen: Multi-Agent Framework for Expository Document Generation in the Architectural Industry](https://aclanthology.org/2025.acl-industry.43/)

**Junjie Jiang**, Haodong Wu, Yongqi Zhang\*, Songyue Guo, Bingcen Liu, Caleb Chen Cao, Ruizhe Shao, Chao Guan, Peng Xu, Lei Chen
- A multi-agent framework that automates method-statement (expository document) generation in the architectural industry
- Decomposes the task into outline generation, section-based content generation, and polishing, each handled by a specialized agent
- A section-based retriever and a section-based chain-of-thought (SeCoT) scheme inject domain knowledge and iterative reasoning
- Achieves a 4.38 ContentScore and is deployed as a web application with industry partners

Keywords: Multi-Agent, Retrieval-Augmented Generation, Document Generation, Large Language Model, Architectural Industry
</div>
</div>

<!--paperRAG-->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Advanced Engineering Informatics</div><img src='images/RAG4CM.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Retrieval augmented generation-driven information retrieval and question answering in construction management](https://www.sciencedirect.com/science/article/pii/S1474034625000515)

Chengke Wu, Wenjun Ding, Qisen Jin, **Junjie Jiang**, Rui Jiang, Qinge Xiao, Longhui Liao, Xiao Li
- A retrieval-augmented generation (RAG) framework for information retrieval and question answering over construction-management documents
- Targets the mismatch between how stakeholders phrase queries and how information is stored in project documents
- Retrieves relevant evidence from heterogeneous project documents to support accurate, prompt responses
- Improves communication efficiency and project continuity in communication-intensive construction management

Keywords: Retrieval-Augmented Generation, Information Retrieval, Question Answering, Construction Management, Large Language Model
</div>
</div>

<!--paper3-->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Expert Systems With Applications</div><img src='images/ESWA.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A compatible detector based on improved YOLOv5 for hydropower device detection in AR inspection system](https://www.sciencedirect.com/science/article/abs/pii/S0957417423005675)

**Junjie Jiang**, Zhile Yang, Chengke Wu, Yuanjun Guo, Meng Yang, Wei Feng\*
- A Compatible detector is proposed for device detection in AR inspection system
- Computation cost is improved by a lightweight backbone network
- A coordinate-based attention module is designed for effective feature fusion
- Optimizing hyperparameters of the new architecture to make the detector robust

[**Code**](https://codeocean.com/capsule/2938777/tree/v1)

Keywords: Object Detection, Augmented Reality, Genetic Algorithm, Power Grid
</div>
</div>

<!--paper4-->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Advanced Engineering Informatics</div><img src='images/ADEI_2.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A teacher–student deep learning strategy for extreme low resolution unsafe action recognition in construction projects](https://www.sciencedirect.com/science/article/pii/S1474034623004226)

Meng Yang, Chengke Wu, Yuanjun Guo, Yong He, Rui Jiang, **Junjie Jiang**, Zhile Yang\*
- A teacher-student deep learning framework is proposed for identifying unsafe behaviours
- The useful feature is captured from extremely low resolution video
- Knowledge learning model and similarity loss function are designed for better training of student network

Keywords: Action Recognition, Knowledge Distillation, Low Resolution, Construction Safety
</div>
</div>

## Patents
<ol class="patent-list">
<li>Yang, Z., <strong>Jiang, J.</strong>, Guo, Y., Liu, X., Wu, C. Method, System, and Related Equipment for Battery Surface Defect Detection Based on Machine Vision. WIPO (PCT) Patent, WO2023226357A1, <a href="./images/PCT1.png">publication</a></li>
<li>Yang, Z., <strong>Jiang, J.</strong>, Liu, X., Guo, Y., Wu, C. A Real-time Optimization Control Method for Charging and Discharging States of a Hybrid Energy Storage System (一种混合储能系统充放电状态实时优化控制方法). National Invention Patent, CN115313447A, <a href="./images/patent_2.png">authorized</a></li>
<li>Guo, Y., <strong>Jiang, J.</strong>, Wu, C., Yang, Z., Hu, T. Method, System, and Related Equipment for Defect Detection Based on Battery Surface Images (基于电池表面图像的缺陷检测方法、系统及相关设备). National Invention Patent, CN115272330A, <a href="./images/patent_3.png">authorized</a></li>
<li>Yang, Z., <strong>Jiang, J.</strong>, Guo, Y., Liu, X., Wu, C. Method, System, and Related Equipment for Battery Surface Defect Detection Based on Machine Vision (基于机器视觉的电池表面缺陷检测方法、系统及相关设备). National Invention Patent, CN114972258B, <a href="./images/patent_1.png">authorized</a></li>
</ol>

# Projects

<!--project-archidocgen-->
<div class='project-box'>
<div class='project-box-image'><img src='projects/archidocgen.gif' alt="ArchiDocGen demo" width="100%"></div>
<div class='project-box-text' markdown="1">

**ArchiDocGen** — Multi-Agent Expository Document Generation for the Architectural Industry

A deployed web application that automatically drafts construction *method statements* end-to-end: outline generation, section-based content generation with retrieval-augmented reasoning, and final polishing — each handled by a specialized agent. Built and deployed with our industry partner [China State Construction Engineering (Hong Kong) Limited](https://www.cscechk.com/tc/bus_haihong2.php), and presented at [ACL 2025 (Industry Track)](https://aclanthology.org/2025.acl-industry.43/).

[**Paper**](https://aclanthology.org/2025.acl-industry.43/)

</div>
</div>

<!--project-dwss-->
<div class='project-box'>
<div class='project-box-image'><img src='projects/agent.gif' alt="DWSS Agent demo" width="100%"></div>
<div class='project-box-text' markdown="1">

**DWSS Agent** — Evidence-Grounded Agent for Digital Engineering Supervision

A natural-language agent for Hong Kong's Digital Works Supervision System (DWSS) that lets project staff query engineering documents and workflow status in plain language. It ingests and indexes scanned / engineering documents (PDF, images, tables), understands a query across multi-turn context, and performs two-stage retrieval — file-level coarse location followed by page-level fine location, asking for clarification when a query is ambiguous. Answers are generated strictly from retrieved evidence, returning source pages and citations and replying *"insufficient evidence"* rather than guessing — an auditable, traceable QA loop that lowers manual lookup cost and improves answer reliability in real construction-supervision scenarios.

</div>
</div>

# Honors
- *2024.01* SIAT President's Scholarship — Excellent Award (top 5%), Shenzhen Institute of Advanced Technology, CAS
- *2024.01* SIAT Outstanding Contribution Award — 2023
- *2024.01* Director's Innovation Award — Outstanding Graduate Student, SIAT, CAS-CUHK (中国科学院香港中文大学深圳先进集成技术研究所)
- *2022.12* The 2022 SEIC Outstanding Contribution Award, Shenzhen Institute of Advanced Technology, CAS
- *2022.06* Excellent Undergraduate Thesis of Shenyang Ligong University, SYLU
- *2019.11* Third Prize, Robot Competition of the School of Mechanical Engineering, SYLU

# Education
- *2025.09 - Present* PhD Student, Data Science and Analytics, HKUST(GZ)
- *2022.05 - 2024.08* Visiting Student, SIAT, Chinese Academy of Sciences
- *2018.09 - 2022.06* B.Eng. Robot Engineering, Shenyang Ligong University

# Experience
- *2024.08 - 2025.08* Research Assistant, HKUST(GZ)
- *2022.05 - 2024.08* Research Assistant, SIAT, Chinese Academy of Sciences
