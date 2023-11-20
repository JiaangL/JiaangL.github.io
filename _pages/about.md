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
I am currently a third-year PhD student at <a href='http://en.ustc.edu.cn/'>University of Science and Technology of China</a>, supervised by Prof. <a href='https://scholar.google.com/citations?user=hxGs4ukAAAAJ&hl=en&oi=ao'>Yongdong Zhang</a>. and Prof. <a href='https://faculty.ustc.edu.cn/maozhendong/zh_CN/index.htm'>Zhendong Mao</a>. I also closely collaborate with  <a href='https://scholar.google.com/citations?user=l2yEbhAAAAAJ&hl=zh-CN&oi=ao'>Quan Wang</a>.
My current research interests lie within machine learning topics about large language models (LLMs), and I am also researching on knowledge graph representation and reasoning. <br/>
<!-- My **CV** can be downloaded <a href="assets/Rui-Chen-Zheng-CV-2023.pdf">here</a>. -->


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
  <!-- - Minor in Business Administration -->
  - Member of Artificial Intelligence (AI) Elite Class.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2023 (Oral)</div><img src='images/Quantization.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Random Entity Quantization for Parameter-Efficient Compositional Knowledge Graph Representation (**Oral**)](https://arxiv.org/abs/2310.15797#)

**Jiaang Li**, Quan Wang, Yi Liu, Licheng Zhang, Zhendong Mao

[**Code**](https://github.com/JiaangL/RandomQuantization)   [**Slides**](files/emnlp2023_slides.pdf)
- Representation Learning on Knowledge Graphs (KGs) is essential for downstream tasks. The dominant approach, KG Embedding (KGE), represents entities with independent vectors and faces the scalability challenge. Recent studies propose an alternative way for parameter efficiency, which represents entities by composing entity-corresponding codewords matched from predefined small-scale codebooks. We refer to the process of obtaining corresponding codewords of each entity as entity quantization, for which previous works have designed complicated strategies. Surprisingly, this paper shows that simple random entity quantization can achieve similar results to current strategies. We analyze this phenomenon and reveal that entity codes, the quantization outcomes for expressing entities, have higher entropy at the code level and Jaccard distance at the codeword level under random entity quantization. Therefore, different entities become more easily distinguished, facilitating effective KG representation. The above results show that current quantization strategies are not critical for KG representation, and there is still room for improvement in entity distinguishability beyond current strategies.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICASSP 2023 (Oral)</div><img src='images/REPORT.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Inductive Relation Prediction from Relational Paths and Context with Hierarchical Transformers (**Oral**)](https://arxiv.org/abs/2304.00215)

**Jiaang Li**, Quan Wang, Zhendong Mao

[**Code**](https://github.com/JiaangL/REPORT)   [**Slides**](files/REPORT_slides.pdf)   [**Video**](https://www.bilibili.com/video/BV1KL411h7y9/?spm_id_from=333.999.0.0&vd_source=422066927d2971b1f78fb59fbff3a263)
- Relation prediction on knowledge graphs (KGs) is a key research topic. Dominant embedding-based methods mainly focus on the transductive setting and lack the inductive ability to generalize to new entities for inference. Existing methods for inductive reasoning mostly mine the connections between entities, i.e., relational paths, without considering the nature of head and tail entities contained in the relational context. This paper proposes a novel method that captures both connections between entities and the intrinsic nature of entities, by simultaneously aggregating RElational Paths and cOntext with a unified hieRarchical Transformer framework, namely REPORT. REPORT relies solely on relation semantics and can naturally generalize to the fully-inductive setting, where KGs for training and inference have no common entities. In the experiments, REPORT performs consistently better than all baselines on almost all the eight version subsets of two fully-inductive datasets. Moreover. REPORT is interpretable by providing each element's contribution to the prediction results.
</div>
</div>

# 🎖 Honors and Awards
- *2023.10* GDC Tech Scholarship. 
- *2020.12* USTC Outstanding Student Scholarship, Bronze Award.
- *2019.10* Institute of Microsystems, CAS Scholarship. 


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