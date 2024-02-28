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

<span class="anchor" id="about-me"></span>

I am currently a Master at [South China University of Techonology (SCUT)](https://www.scut.edu.cn/en/), advised by [Prof. Kui Jia](http://kuijia.site/). I received my bachelor degree from the same university (i.e. SCUT) in 2023, and expect to obtain my Master degree in 2026. 

I mainly focus on **Computer Vision**. My current research interests include Semantic Perception and Domain Adaptation. Recently, I am working on Domain Adaptation.


# 📝 Publications

<div class="paper-box"><div class="paper-box-image"><div><div class="badge">arXiv 2023</div><img src="images/wesam.webp" alt="sym" width="100%"></div></div>
<div class="paper-box-text" markdown="1">

[Improving the Generalization of Segmentation Foundation Model under Distribution Shift via Weakly Supervised Adaptation](http://arxiv.org/abs/2312.03502)

 **Haojie Zhang\***, Yongyi Su\*, Xun Xu✝, Kui Jia

[**Project**](https://zhang-haojie.github.io/project-pages/wesam.html) | [**Code**](https://github.com/zhang-haojie/wesam)

- We propose a task-agnostic solution to adapt the SAM model for diverse downstream segmentation tasks using self-training without access to the source dataset. By leveraging weak supervisions such as bounding boxes, point-wise annotations, and coarse segmentation masks, we enhance the adaptation effectiveness, as demonstrated through extensive experiments on 5 types of downstream instance segmentation tasks.
</div>
</div>


# 📖 Educations
- *2023.09 - Now*, Master, South China University of Technology, Guangzhou.
- *2019.09 - 2023.06*, Undergraduate, South China University of Technology, Guangzhou.