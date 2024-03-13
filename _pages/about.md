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

I am now working on the research of deep learning and large language model adaption to tabular data fields. If you are seeking any form of academic discussion or cooperation, please feel free to email me at [jyansir@zju.edu.cn](mailto:jyansir@zju.edu.cn).

I graduated from [Chu Kochen Honors College](http://ckc.zju.edu.cn/ckcen/main.htm), Zhejiang University (浙江大学竺可桢学院) with a bachelor's degree and am a full-time PhD student in the Department of Computer Science and Technology, Zhejiang University (浙江大学计算机科学与技术学院), advised by [Jian Wu (吴健)](https://person.zju.edu.cn/0004274). I also collaborate with the researcher [Jintai Chen (陈晋泰)](https://scholar.google.com/citations?user=ZiY3xYEAAAAJ) from the University of Illinois Urbana-Champaign closely.

My research interest includes tabular language model pre-training, relational deep learning and neural architecture engineering.

I am also an amateur photographer and ACG enthusiast, and very willing to join relevant offline activities in my spare time.


<!-- # 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2024</div><img src='images/tp-model.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Making Pre-trained Language Models Great on Tabular Prediction](https://openreview.net/pdf?id=anzIzGZuLi)

**Jiahuan Yan**, Bo Zheng, Hongxia Xu, Yiheng Zhu, Danny Chen, Jimeng Sun, Jian Wu, Jintai Chen, **<span style="color:red">(SpotLight, Notable Top 5%)</span>**

[**repo**](https://github.com/jyansir/tp-berta)
- Background: Feature heterogeneity poses challenges on tabular transfer learning. As versatile learners, pre-trained language models (LMs) serve to transfer knowledge through the text space, but current LM-based tabular models ignore the sensitivity of numerical values and tabular feature organization.
- **TL;DR:** This work proposed relative magnitude tokenization, a distributed numerical feature embedding technique, and intra-feature attention, a reasonably contextualized mechanism, both for tabular feature adaption to the modern Transformer-based LM architecture.
- **Academic Impact:** The resulting pre-trained LM TP-BERTa surpasses non-LM baselines on 145 downstream tabular prediction datasets, pivot analysis exhibits further significant improvement when the discrete feature dominates.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2023</div><img src='images/t2g-model.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[T2G-Former: Organizing tabular features into relation graphs promotes heterogeneous feature interaction](https://ojs.aaai.org/index.php/AAAI/article/view/26272)

Jiahuan Yan, Jintai Chen, Yixuan Wu, Danny Ziyi Chen, Jian Wu, **<span style="color:red">(Oral, Top 20%)</span>**

[**repo**](https://github.com/jyansir/t2g-former)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2023</div><img src='images/t2t-model.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Text2Tree: Aligning Text Representation to the Label Tree Hierarchy for Imbalanced Medical Classification](https://aclanthology.org/2023.findings-emnlp.517.pdf)

Jiahuan Yan, Haojun Gao, Zhang Kai, Weize Liu, Danny Chen, Jian Wu, Jintai Chen, **EMNLP-Findings**

[**repo**](https://github.com/jyansir/text2tree)
</div>
</div>

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Educations
- *2020.09 - now*,     PhD, Zhejiang University, Hangzhou. 
- *2016.09 - 2020.06*, Undergraduate, Chu Kochen Honors College, Zhejiang Univeristy, Hangzhou.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->