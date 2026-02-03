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

I am currently a Master’s student at [South China University of Technology (SCUT)](https://www.scut.edu.cn/en/), advised by Prof. [Kui Jia](http://kuijia.site/) and Dr. [Xun Xu](https://alex-xun-xu.github.io/). I received my Bachelor’s degree with distinction from SCUT in 2023, and expect to obtain my Master’s degree in 2026. From April to November 2024, I was a visiting student at the Department of Automation, Tsinghua University, advised by Prof. Jianhua Tao.

My lifelong research goal is to bridge perception, understanding, and imagination in intelligent systems, enabling machines to see, comprehend, and create as humans do. My current research interests include **generative models**, **vision-language models**, and **foundational vision models**. I am passionate about advancing the frontiers of computer vision and artificial intelligence, and am always eager to explore new ideas and collaborate with others.

**Research Interests:**  
- Generative Models (Diffusion models, controllable video generation, talking head synthesis)  
- Vision-Language Models (MLLMs, unified vision tasks, visual grounding)  
- Foundational Vision Models (Segmentation foundation models, domain adaptation, semantic perception)  

I am always open to academic discussions and collaborations. If you are interested in my research or have any questions, feel free to contact me!

<!-- > <span style="color:red;"><i><b>News:</b> I am actively seeking job opportunities related to <b>multimodal large models</b> or <b>generative models</b>. If you have any relevant positions or collaborations, please feel free to contact me!</i></span> -->


# 📝 Selected Publications

<!-- 4. Patch-as-Decodable-Token (ICLR 2026) -->
<div class="paper-box"><div class="paper-box-image"><div><div class="badge">ICLR 2026</div><img src="images/padt.webp" alt="vrt" width="100%"></div></div>
<div class="paper-box-text" markdown="1">

**Patch-as-Decodable-Token: Towards Unified Multi-Modal Vision Tasks in MLLMs**  
Yongyi Su\*, **Haojie Zhang\***, Shijie Li, Nanqing Liu, Jingyi Liao, Junyi Pan, Yuan Liu, Xiaofen Xing, Chong Sun, Chen Li, Nancy F. Chen, Shuicheng Yan, Xulei Yang, Xun Xu  
The International Conference on Learning Representations (ICLR), 2026  
[**arXiv**](https://arxiv.org/abs/2510.01954) | [**Code**](https://github.com/Gorilla-Lab-SCUT/PaDT.git)

- We propose the Visual Reference Token (VRT), which is generated from the visual features of a query image and can serve as a target referent. The unified decoder designed based on VRT supports multiple vision tasks. To optimize VRT, we dynamically expand the embedding table of the MLLM and jointly optimize both visual and textual tokens via an autoregressive loss, achieving deep multi-modal fusion.

</div>
</div>

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
**Haojie Zhang**, Yongyi Su, Nanqing Liu, Xulei Yang, Kui Jia, Xun Xu  
Under review at IEEE TPAMI 2025  
[**Preprint**](https://www.preprints.org/manuscript/202510.1640) | [**Code**](https://github.com/zhang-haojie/wesam)

- We propose WeSAM++, which introduces patch-level contrastive loss for better feature alignment and incorporates Masked Image Modeling to enhance encoder consistency and robustness. Our method achieves superior generalization on unsupervised adaptation, open-vocabulary segmentation, and SAM2 adaptation.

</div>
</div>

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

<!-- 5. PointSAM (TGRS 2025) -->
<div class="paper-box"><div class="paper-box-image"><div><div class="badge">TGRS 2025</div><img src="images/pointsam.webp" alt="pointsam" width="100%"></div></div>
<div class="paper-box-text" markdown="1">

**PointSAM: Pointly-Supervised Segment Anything Model for Remote Sensing Images**  
Nanqing Liu, Xun Xu, Yongyi Su, **Haojie Zhang**, Heng-Chao Li  
IEEE Transactions on Geoscience and Remote Sensing (TGRS), 2025  
[**arXiv**](https://arxiv.org/abs/2409.13401)

- We propose PointSAM, an enhanced self-training framework for remote sensing image segmentation that introduces prototype constraints via the Hungarian algorithm and negative prompt calibration with non-overlapping masks, effectively reducing pseudo-label noise and object merging.

</div>
</div>

<!-- 6. Sur2f (ECCV 2024) -->
<div class="paper-box"><div class="paper-box-image"><div><div class="badge">ECCV 2024</div><img src="images/sur2f.webp" alt="sur2f" width="100%"></div></div>
<div class="paper-box-text" markdown="1">

**Sur<sup>2</sup>f: A Hybrid Representation for High-Quality and Efficient Surface Reconstruction from Multi-view Images**  
Zhangjin Huang, Zhihao Liang, **Haojie Zhang**, Yangkai Lin, Kui Jia  
European Conference on Computer Vision (ECCV), 2024  
[**arXiv**](https://arxiv.org/abs/2401.03704) | [**Project**](https://huang-zhangjin.github.io/project-pages/sur2f.html)

- We propose Sur2f, a multi-view 3D reconstruction framework that jointly learns an implicit SDF and an explicit deformable mesh via a neural shader; by synchronizing mesh deformation and enabling surface-guided sampling, Sur2f efficiently reconstructs detailed and complex surfaces from multi-view images.

</div>
</div>


# 🎓 Education

- *2024.04 - 2024.11*, Visiting Student, Department of Automation, Tsinghua University, Beijing  
  Advised by Prof. Jianhua Tao.

- *2023.09 - 2026.06*, MSc in Information and Communication Engineering, South China University of Technology, Guangzhou  
  Supervised by Prof. Kui Jia.  

- *2019.09 - 2023.06*, BTech in Information Engineering, South China University of Technology, Guangzhou  


# 💼 Internship Experience

- **Tencent Technology and Engineering Group**, Hunyuan Team, Shenzhen, 2025.11 – Now

- **Tencent WeChat Business Group**, WeChat Vision, Shenzhen, 2025.04 – 2025.10  

- **Tencent Interactive Entertainment Group**, LIGHTSPEED, Shenzhen, 2024.12 – 2025.03  

