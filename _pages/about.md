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

I am currently a Master at [South China University of Techonology](https://www.scut.edu.cn/en/) (SCUT), advised by Prof. [Kui Jia](http://kuijia.site/) and Dr. [Xun Xu](https://alex-xun-xu.github.io/). I received my bachelor degree from the same university (i.e. SCUT) in 2023, and expect to obtain my Master degree in 2026. 

I mainly focus on **Computer Vision**. My current research interests include Semantic Perception, Domain Adaptation and 3D Reconstruction. I really enjoy my research and if you are interested or troubled by it, you are welcome to discuss it with me.


# 📝 Publications

<div class="paper-box"><div class="paper-box-image"><div><div class="badge">arXiv 2023</div><img src="images/wesam.webp" alt="sym" width="100%"></div></div>
<div class="paper-box-text" markdown="1">

**Improving the Generalization of Segmentation Foundation Model under Distribution Shift via Weakly Supervised Adaptation**

 **Haojie Zhang\***, Yongyi Su\*, Xun Xu<sup>+</sup>, Kui Jia
 
IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2024

[**Paper**](http://arxiv.org/abs/2312.03502) | [**Project**](https://zhang-haojie.github.io/project-pages/wesam.html) | [**Code**](https://github.com/zhang-haojie/wesam)

- We propose a task-agnostic solution to adapt the SAM model for diverse downstream segmentation tasks using self-training without access to the source dataset. By leveraging weak supervisions such as bounding boxes, point-wise annotations, and coarse segmentation masks, we enhance the adaptation effectiveness, as demonstrated through extensive experiments on 5 types of downstream instance segmentation tasks.

</div>
</div>

<div class="paper-box"><div class="paper-box-image"><div><div class="badge">arXiv 2023</div><img src="images/sur2f.png" alt="sym" width="100%"></div></div>
<div class="paper-box-text" markdown="1">

**Sur<sup>2</sup>f: A Hybrid Representation for High-Quality and Efficient Surface Reconstruction from Multi-view Images**

 Zhangjin Huang\*, Zhihao Liang\*, **Haojie Zhang**, Yangkai Lin, Kui Jia

Preprint, 2024

[**Paper**](https://arxiv.org/abs/2401.03704) | [**Project**](https://huang-zhangjin.github.io/project-pages/sur2f.html) | [**Code**](https://huang-zhangjin.github.io/project-pages/comming_soom.html)

- We propose a new hybrid representation, termed Sur<sup>2</sup>f, that can enjoy the benefits of both explicit and implicit surface representations. This is achieved by learning two parallel streams of an implicit SDF and an explicit surrogate surface mesh, both of which, by rendering, receive supervision from multi-view image observations.

</div>
</div>


# 📖 Educations
- *2023.09 - Now*, Master, South China University of Technology, Guangzhou.
- *2019.09 - 2023.06*, Undergraduate, South China University of Technology, Guangzhou.