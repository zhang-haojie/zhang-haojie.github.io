---
permalink: /
title: ""
excerpt: ""
author_profile: false
show_masthead: false
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

<section class="hero-flow">
  <div class="hero-flow__top">
    <div class="hero-flow__avatar-wrap">
      <img class="hero-flow__avatar" src="images/zhang.haojie.jpg" alt="Haojie Zhang portrait">
    </div>
  </div>
  <p class="hero-flow__eyebrow">Multimodal AI · Generative Models · Computer Vision</p>
  <h1 class="hero-flow__title">Haojie Zhang</h1>
  <p class="hero-flow__subtitle">
    M.Sc. student at <a href="https://www.scut.edu.cn/en/">South China University of Technology</a>,
    focused on building intelligent systems that can perceive, understand, and create.
  </p>
  <div class="hero-flow__actions">
    <a class="hero-chip" href="mailto:eehaojiezhang@gmail.com">Email</a>
    <a class="hero-chip" href="https://scholar.google.com/citations?pli=1&authuser=1&user=waixiQgAAAAJ">Google Scholar</a>
    <a class="hero-chip" href="https://github.com/zhang-haojie">GitHub</a>
  </div>
  <div class="hero-flow__meta">
    <span>Guangzhou, China</span>
    <span>SCUT</span>
    <span>Open to collaborations</span>
  </div>
</section>

<section class="flow-section" markdown="1">
  <div class="section-heading">
    <span class="section-heading__index">01</span>
    <div>
      <h2>About</h2>
      <p>Researcher working across generative modeling, multimodal large language models, and foundational vision systems.</p>
    </div>
  </div>

  <div class="glass-panel intro-panel">
    <p>
      I am currently an M.Sc. student in Information and Communication Engineering at
      <a href="https://www.scut.edu.cn/en/">South China University of Technology (SCUT)</a>, advised by
      Prof. <a href="http://kuijia.site/">Kui Jia</a> and Dr.
      <a href="https://alex-xun-xu.github.io/">Xun Xu</a>. I previously received my B.Eng. in Information
      Engineering (Innovation Class) from SCUT with distinction in 2023. From April 2024 to November 2024,
      I was a visiting student at the Department of Automation, Tsinghua University, where I worked with
      Prof. Jianhua Tao.
    </p>
    <p>
      My long-term goal is to bridge perception, understanding, and imagination in intelligent systems.
      Recent work includes talking video synthesis, unified multimodal vision tasks, segmentation foundation
      model adaptation, and multimodal evaluation benchmarks.
    </p>
  </div>

  <div class="interest-grid">
    <div class="glass-panel interest-card">
      <h3>Generative Models</h3>
      <p>Diffusion models, controllable video generation, talking head synthesis, image editing.</p>
    </div>
    <div class="glass-panel interest-card">
      <h3>Multimodal LLMs</h3>
      <p>Unified multimodal vision tasks, dense prediction with MLLMs, multimodal evaluation.</p>
    </div>
    <div class="glass-panel interest-card">
      <h3>Foundational Vision</h3>
      <p>Segmentation foundation models, domain adaptation, semantic perception.</p>
    </div>
  </div>
</section>

<section class="flow-section" markdown="1">
  <div class="section-heading">
    <span class="section-heading__index">02</span>
    <div>
      <h2>Selected Publications</h2>
      <p>Grouped by research direction and ordered to match my CV.</p>
    </div>
  </div>

## Foundational Vision Models

<!-- 1. WeSAM (CVPR 2024) -->
<div class="paper-box"><div class="paper-box-image"><div><div class="badge">CVPR 2024</div><img src="images/wesam.webp" alt="wesam" width="100%"></div></div>
<div class="paper-box-text" markdown="1">

**Improving the Generalization of Segmentation Foundation Model under Distribution Shift via Weakly Supervised Adaptation**  
**Haojie Zhang**, Yongyi Su, Xun Xu<sup>+</sup>, Kui Jia  
IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2024  
[**Paper**](https://ieeexplore.ieee.org/document/10657214) | [**arXiv**](http://arxiv.org/abs/2312.03502) | [**Project**](https://zhang-haojie.github.io/project-pages/wesam.html) | [**Code**](https://github.com/zhang-haojie/wesam)

- We propose WeSAM, a weakly supervised self-training framework with anchor regularization and low-rank adaptation, which enables efficient adaptation of foundation models (e.g., SAM) for diverse image segmentation tasks. WeSAM outperforms SAM and other state-of-the-art methods on five challenging benchmarks.

</div>
</div>

<!-- 2. WeSAM++ (TPAMI under review) -->
<div class="paper-box"><div class="paper-box-image"><div><div class="badge">TPAMI Under Review</div><img src="images/wesampp.webp" alt="wesampp" width="100%"></div></div>
<div class="paper-box-text" markdown="1">

**Improving the Generalization of Segmentation Foundation Models via Weakly-Supervised and Unsupervised Adaptation**  
**Haojie Zhang**, Yongyi Su, Nanqing Liu, Xulei Yang, Xiangyu Yue, Kui Jia, Xun Xu  
Under review at IEEE TPAMI 2025  
[**Preprint**](https://www.preprints.org/manuscript/202510.1640) | [**Code**](https://github.com/zhang-haojie/wesam)

- We propose WeSAM++, which introduces patch-level contrastive loss for better feature alignment and incorporates Masked Image Modeling to enhance encoder consistency and robustness. Our method achieves superior generalization on unsupervised adaptation, open-vocabulary segmentation, and SAM2 adaptation.

</div>
</div>

## Generative Models

<!-- 3. LetsTalk (IEEE TMM) -->
<div class="paper-box"><div class="paper-box-image"><div><div class="badge">TMM 2026</div><img src="images/letstalk.webp" alt="letstalk" width="100%"></div></div>
<div class="paper-box-text" markdown="1">

**Efficient Long-duration Talking Video Synthesis with Linear Diffusion Transformer under Multimodal Guidance**  
**Haojie Zhang**, Zhihao Liang, Ruibo Fu, Bingyan Liu, Zhengqi Wen, Xuefei Liu, Jianhua Tao, Yaling Liang  
IEEE Transactions on Multimedia (TMM), 2026  
[**arXiv**](https://arxiv.org/abs/2411.16748) | [**Code**](https://github.com/zhang-haojie/letstalk)

- We propose LetsTalk, a diffusion transformer for audio-driven portrait animation. By leveraging DC-VAE and linear attention, LetsTalk enables efficient multimodal fusion and consistent portrait generation, while memory bank and noise-regularized training further improve the quality and stability of long-duration videos.

</div>
</div>

<!-- 4. MuSS (ACM MM 2026 under review) -->
<div class="paper-box"><div class="paper-box-image"><div><div class="badge">ACM MM 2026 Under Review</div><img src="images/MuSS.jpg" alt="muss" width="100%"></div></div>
<div class="paper-box-text" markdown="1">

**MuSS: A Large-Scale Dataset and Cinematic Narrative Benchmark for Multi-Shot Subject-to-Video Generation**  
**Haojie Zhang**, Di Wu, Bingyan Liu, Linjie Zhong, Yuancheng Wei, Xingsong Ye, Nanqing Liu  
Under review at ACM Multimedia (ACM MM), 2026

- We introduce MuSS, a large-scale cinematic multi-shot dataset and benchmark for subject-to-video generation, designed to evaluate narrative coherence, cross-shot identity consistency, and visual storytelling quality.

</div>
</div>

## Multimodal Large Language Models

<!-- 5. PaDT (ICLR 2026) -->
<div class="paper-box"><div class="paper-box-image"><div><div class="badge">ICLR 2026</div><img src="images/padt.webp" alt="padt" width="100%"></div></div>
<div class="paper-box-text" markdown="1">

**Patch-as-Decodable-Token: Towards Unified Multi-Modal Vision Tasks in MLLMs**  
Yongyi Su\*, **Haojie Zhang\***, Shijie Li, Nanqing Liu, Jingyi Liao, Junyi Pan, Yuan Liu, Xiaofen Xing, Chong Sun, Chen Li, Nancy F. Chen, Shuicheng Yan, Xulei Yang, Xun Xu  
The International Conference on Learning Representations (ICLR), 2026  
[**arXiv**](https://arxiv.org/abs/2510.01954) | [**Code**](https://github.com/Gorilla-Lab-SCUT/PaDT.git)

- We propose Patch-as-Decodable Token (PaDT), a unified multimodal paradigm that uses Visual Reference Tokens to let MLLMs directly generate diverse dense visual predictions, achieving strong performance across multiple perception tasks.

</div>
</div>

<!-- 6. DiffCap-Bench (ACM MM 2026 under review) -->
<div class="paper-box"><div class="paper-box-image"><div><div class="badge">ACM MM 2026 Under Review</div><img src="images/DiffCap.jpg" alt="diffcap" width="100%"></div></div>
<div class="paper-box-text" markdown="1">

**DiffCap-Bench: A Comprehensive, Challenging, Robust Benchmark for Image Difference Captioning**  
Yuancheng Wei\*, **Haojie Zhang\***, Linli Yao, Lei Li, Jiali Chen, Tao Huang, Yiting Lu, Duojun Huang, Xin Li, Zhao Zhong  
Under review at ACM Multimedia (ACM MM), 2026

- We introduce DiffCap-Bench, a challenging benchmark for image difference captioning, together with an LLM-as-a-Judge evaluation protocol that aligns well with human judgment and supports downstream image editing data construction.

</div>
</div>

</section>

<section class="flow-section" markdown="1">
  <div class="section-heading">
    <span class="section-heading__index">03</span>
    <div>
      <h2>Education</h2>
      <p>Academic trajectory across SCUT and Tsinghua University.</p>
    </div>
  </div>

- *2024.04 - 2024.11*, Visiting Student, Department of Automation, Tsinghua University, Beijing  
  Advised by Prof. Jianhua Tao.

- *2023.09 - 2026.06*, MSc in Information and Communication Engineering, South China University of Technology, Guangzhou  
  Supervised by Prof. Kui Jia and collaborating with Dr. Xun Xu.

- *2019.09 - 2023.06*, B.Eng. in Information Engineering (Innovation Class), South China University of Technology, Guangzhou  
  Graduated with distinction, GPA 3.64/4.0, weighted average 86.1/100.
</section>

<section class="flow-section" markdown="1">
  <div class="section-heading">
    <span class="section-heading__index">04</span>
    <div>
      <h2>Internship Experience</h2>
      <p>Industry experience spanning video generation, vision systems, and multimodal applications.</p>
    </div>
  </div>

- *2025.10 - 2026.03*, Tencent Technology and Engineering Group, Hunyuan Team, Shenzhen
- *2025.04 - 2025.10*, Tencent WeChat Business Group, WeChat Vision, Shenzhen
- *2024.12 - 2025.03*, Tencent Interactive Entertainment Group, LIGHTSPEED, Shenzhen
</section>

<section class="flow-section" markdown="1">
  <div class="section-heading">
    <span class="section-heading__index">05</span>
    <div>
      <h2>Honors</h2>
      <p>Selected awards and academic recognitions.</p>
    </div>
  </div>

- First Prize, Guangdong Undergraduate Mathematical Contest in Modeling, 2021
- National Encouragement Scholarship
- Second Prize Scholarship
- Merit Student and Excellent Student Cadre
</section>
