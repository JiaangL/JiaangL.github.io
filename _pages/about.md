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

Hi there! My name is Jiaang Li (李家昂).<br/>
I am currently a PhD candidate at <a href='http://en.ustc.edu.cn/'>University of Science and Technology of China</a>, supervised by Prof. <a href='https://scholar.google.com/citations?user=hxGs4ukAAAAJ&hl=en&oi=ao'>Yongdong Zhang</a>. and Prof. <a href='https://scholar.google.com/citations?hl=zh-CN&user=m-0P8sgAAAAJ'>Zhendong Mao</a>. I also closely collaborate with  <a href='https://scholar.google.com/citations?user=l2yEbhAAAAAJ&hl=zh-CN&oi=ao'>Quan Wang</a>.
My current research interests lie within knowledge topics about large language models, and I am also researching on knowledge graph representation and reasoning. <br/>
My **CV** can be downloaded *<a href="assets/Jiaang Li CV en.pdf">here</a>*.


<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

<!-- 
# 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2023.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Educations
- *2021.09 - 2026.06 (Expected)*, **PhD Student** in Information and Comunication Engineering, *University of Science and Technology of China*
  - Supervised by Prof. Yongdong Zhang and Prof. Zhendong Mao
- *2017.09 - 2021.06*, **Bachelor of Engineering** in Automation, *University of Science and Technology of China*  
  - Thesis: Learning and Reasoning with Complex Relations in Knowledge Graphs
  <!-- - GPA: 3.89/4.3, 90.46/100 (Top 5%) -->
  - Member of Artificial Intelligence (AI) Elite Class.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025</div><img src='images/MixLoRA.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[ELDER: Enhancing Lifelong Model Editing with Mixture-of-LoRA](https://arxiv.org/pdf/2408.11869)

**Jiaang Li**, Quan Wang, Zhongnan Wang, Yongdong Zhang, Zhendong Mao

[**Code**](https://github.com/JiaangL/ELDER)
- Current Lifelong Model Editing approaches manage sequential edits through discrete data-adapter mappings. They assign a unique adapter for each new edit via key-value mapping, making them sensitive to minor data changes. Such changes can incorrectly map an edit to a wrong adapter, causing inconsistent outputs and poor generalization.
- In contrast, our method maps each edit to a mixed combination of preset adapters, ensuring minor data changes don't entirely alter the adapter parameters, thereby enhancing generalization. 
- Additionally, our method is scalable by sharing preset adapters across increasing edits, while previous discrete methods require a separate adapter for each edit data.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2023 (Oral)</div><img src='images/Quantization.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Random Entity Quantization for Parameter-Efficient Compositional Knowledge Graph Representation](https://arxiv.org/abs/2310.15797#)

**Jiaang Li**, Quan Wang, Yi Liu, Licheng Zhang, Zhendong Mao

[**Code**](https://github.com/JiaangL/RandomQuantization)   [**Slides**](files/emnlp2023_slides.pdf)
- Knowledge Graph (KG) Embedding represents entities with independent vectors and faces the scalability challenge. Recent studies propose compositional KG representation for parameter efficiency. We abstract the existing works, and define the process of obtaining corresponding codewords for each entity as entity quantization, for which previous works have designed complicated strategies.
- Reveal that simple random entity quantization can achieve similar results to current strategies. Further analyses reveal that entity codes have higher entropy at the code level and Jaccard distance at the codeword level under random entity quantization, which make different entities more distinguishable. 
- We prove that the random quantization strategy is already good enough for KG representation. Future work could focusing on improving entity distinguishability from other aspects.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICASSP 2023 (Oral)</div><img src='images/REPORT.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Inductive Relation Prediction from Relational Paths and Context with Hierarchical Transformers](https://arxiv.org/abs/2304.00215)

**Jiaang Li**, Quan Wang, Zhendong Mao

[**Code**](https://github.com/JiaangL/REPORT)   [**Slides**](files/REPORT_slides.pdf)   [**Video**](https://www.bilibili.com/video/BV1KL411h7y9/?spm_id_from=333.999.0.0&vd_source=422066927d2971b1f78fb59fbff3a263)
- Propose a method that performs inductive reasoning on Knowledge Graphs and can naturally generalize to the fully-inductive setting, where KGs for training and inference have no common entities.
- Capture both connections between entities and the intrinsic nature of each single entity, by simultaneously aggregating relational paths and context. Use the aggregated upper-level semantics for reasoning to improve model prediction performance.
- Design a Hierarchical Transformer model for path-neighborhood encoding and information aggregation. Our proposed model performs consistently better than all baselines on almost all the eight version subsets of two fully-inductive datasets. Moreover. we design a method to interpret our method by providing each element’s contribution to the prediction results.
</div>
</div>

# 🎖 Honors and Awards
- *2023.10* GDC Tech Scholarship. 
- *2019.10* Institute of Microsystems, CAS Scholarship.
- *2017 & 2018 & 2021* USTC Outstanding Student Scholarship.


# 📚 Experience
- *2023 Spring*, Teaching Assistant, Machine Learning and its applications, USTC. (by Prof. Zhendong Mao)
- *2022.9-2023.2*, Research Intern, State Key Laboratory of Communication Content Cognition.
- *2020.5-2020.8*, Summer Research Intern (Remote), University of California, Santa Barbara. (Hosted by Prof. Yufei Ding)
- *2019.7-2019.8*, Summer School in Artificial Intelligence and Robotics, Imperial College London, UK. (Hosted by Prof. Guanzhong Yang, Best Overall Project)

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->
