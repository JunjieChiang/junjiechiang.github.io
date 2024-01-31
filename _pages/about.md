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
I am now a research assistant at Shenzhen Institute of Advanced Technology CAS, supervised by [Prof. Zhile Yang](https://scholar.google.com/citations?user=XcXa6wEAAAAJ&hl=zh-CN&oi=ao) and [A/Prof. Chengke Wu](https://scholar.google.com/citations?user=DzwZYrQAAAAJ&hl=zh-CN). My current research interests include:
- Knowledge Engineering
- Natural Language Processing
- Deep Learning
- AI4Industry

Previously, I graduated from Shenyang Ligong University with a bachelor’s degree in 2022. My research directions include the intersection of natural language processing, knowledge engineering, computer vision and machine learning, and their applications in areas such as smart construction and smart grids.

➡️ Download my [Resumé](./uploads/Jiang's CV.pdf)

# 🔥 News
- *2023.10*: &nbsp;🎉🎉 Released a corpus and a dataset for entity-property relation extraction in CEM industry. For more details see [here](https://github.com/Construction-Material/Construction-Dataset-CONSD).
- *2023.10*: &nbsp;🎉🎉 Released the code of relation extraction for construction documents. For more details see [here](https://github.com/Construction-Material/Ontology-for-Relation-Extraction-Ont4RE-).
- *2023.04*: &nbsp;🎉🎉 Released the code of hydropower device detection. For more details see [here](https://codeocean.com/capsule/2938777/tree/v1)

# 📑 Publications 

## Preprint
<!--paper1-->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Automation in Construction</div><img src='images/AIC.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Ontology-based distant supervision for extracting entity-property relations in construction documents](https://github.com/JunjieChiang/Preprints/blob/main/Ontology-based%20distant%20supervision%20for%20extracting%20entity-property%20relations%20in%20construction%20documents.pdf)

**Junjie Jiang**, Chengke Wu*, Wenjie Sun, Yong He, Yuanjun Guo, Su Yang, Zhile Yang
- A novel framework Ont4RE is for distantly supervised relation extraction from CEM documents
- Developed a domain ontology CEMO covering domain classes
- Achieved distantly supervised annotation by entity-class matching using semantic similarity
- A pre-trained BERT is developed for entity-property relation extraction

[**Code Here**](https://github.com/Construction-Material/Ontology-for-Relation-Extraction-Ont4RE-) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

Keywords: Distant Supervision, Relation Extraction, Ontology, BERT, Construction Industry 
</div>
</div>

## Published
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
- Yang, Z., **Jiang, J.**, Guo, Y., Liu, X., Wu, C. Method, System, and Related Equipment for Battery Surface Defect Detection Based on Machine Vision(基于机器视觉的电池表面缺陷检测方法、系统及相关设备). Invention patent, CN114972258B, [authorized](./images/patent_1.png)
- Yang, Z., **Jiang, J.**, Liu, X., Guo, Y., Wu, C. A Real-time Optimization Control Method for Charging and Discharging States of a Hybrid Energy Storage System(一种混合储能系统充放电状态实时优化控制方法). Invention patent, CN115313447A, [authorized](./images/patent_2.png)
- Guo, Y., **Jiang, J.**, Wu, C., Yang, ., Hu, T. Method, System, and Related Equipment for Defect Detection Based on Battery Surface Images(基于电池表面图像的缺陷检测方法、系统及相关设备). Invention patent, CN115272330A, [authorized](./images/patent_3.png)


# 🎖 Honors and Awards
- *2024.01* President's Scholarship-Excellent Award (top 5%), Shenzhen Institute of Advanced Technology, CAS
- *2024.01* Director's Innovation Award-Outstanding Graduate Student, Shenzhen Institute of Advanced Integrated Technology, CAS-CUHK
- *2022.12* The SEIC Outstanding Contribution Award, Shenzhen Institute of Advanced Technology, CAS
- *2022.06* Excellent Undergraduate Thesis of Shenyang Ligong University, SYLU
- *2019.11* Third Prize in Robot Competition of the Faculty of Mechanical Engineering, SYLU

# 📖 Educations
- *2022.06 - Present*, Visiting Student, Shenzhen Institute of Advanced Technology, Chinese Academy of Sciences
- *2018.06 - 2022.09*, Undergraduate, Shenyang Ligong University

<!-- # 💬 Invited Talks
- *2021.06*, Nanjing Normal University 
- *2021.03*, Nanjing Normal University
-->

# 💻 Working
- *2023.06 - now*, Research Assistant, Shenzhen Institute of Advanced Technology, Chinese Academy of Sciences, Shenzhen.
- *2022.05 - 2022.06*, Intern, Zhongke Hangmai CNC Software Shenzhen Co.,Ltd, Shenzhen.
- *2020.05 - 2020.08*, Database Engineer (Internship), Guangdong Creawor Technology Development Co.,Ltd, Guiyang.