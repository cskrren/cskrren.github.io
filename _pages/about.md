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

I am a first-year PhD candidate jointly supervised by Shanghai Jiao Tong University and Shanghai Artificial Intelligence Laboratory, under the primary guidance of [**Prof. Bo Dai**](https://scholar.google.com/citations?user=KNWTvgEAAAAJ). Currently, I am also a research intern at the Embodied AI Center of Shanghai AI Lab, co-advised by [**Dr. Mulin Yu**](https://scholar.google.com/citations?user=w0Od3hQAAAAJ) and [**Dr. Linning Xu**](https://scholar.google.com/citations?user=I9Lrbs4AAAAJ). Prior to my doctoral studies, I received my Bachelor of Engineering degree from Tongji University, where I conducted research on HDR reconstruction for dynamic scenes under the supervision of [**Prof. Zhangkai Ni**](https://scholar.google.com/citations?user=68IcrE4AAAAJ).

My research interests lie in 3D reconstruction, neural rendering, and scene relighting. I have published papers in top-tier computer vision conferences and journals including CVPR, NIPS, RSS, TPAMI, IJCV and TOG, with my publications accumulating 100+ Google Scholar citations.

# 🔥 News
- *2025.09*: &nbsp;🎉 Our MV-CoLight on Multi-view Object Compositing was accepted to NIPS 2025.
- *2025.08*: &nbsp;🎉 One paper on Unposed Novel View Synthesis was accepted to SIGGRAPH Asia 2025 (ACM TOG).
- *2025.06*: &nbsp;🎉 Our SMHDR on Multi-view HDR Reconstruction was accepted to IJCV 2025.
- *2025.05*: &nbsp;🎉 Our Octree-GS on LOD-Structured 3D Gaussians was accepted to TPAMI 2025.
- *2025.04*: &nbsp;🎉 One paper on One-Shot Manipulation was accepted to RSS 2025.
- *2025.02*: &nbsp;🎉 Our Horizon-GS on Aerial-to-Ground Scene Reconstruction was accepted to CVPR 2025.
- *2024.07*: &nbsp;🎓 Graduated from Tongji University.

# 📝 Publications 

(†: corresponding author; * :equal contribution)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGGRAPH Asia 2025 (ACM TOG)</div><img src='images/AnySplat.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AnySplat: Feed-forward 3D Gaussian Splatting from Unconstrained Views](https://arxiv.org/abs/2505.23716)

Lihan Jiang*, Yucheng Mao*, Linning Xu, Tao Lu, **Kerui Ren**, Yichen Jin, Xudong Xu, Mulin Yu, Jiangmiao Pang, Feng Zhao†, Dahua Lin, Bo Dai†

[**Project**](https://city-super.github.io/anysplat/) [**Code**](https://github.com/OpenRobotLab/AnySplat) [**Paper**](https://arxiv.org/pdf/2505.23716)
- We introduce AnySplat, a feed‑forward network for novel‑view synthesis from uncalibrated image collections in both sparse‑ and dense‑view scenarios.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NIPS 2025</div><img src='images/MVCoLight.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MV-CoLight: Efficient Object Compositing with Consistent Lighting and Shadow Generation](https://arxiv.org/abs/2505.21483)

**Kerui Ren**, Jiayang Bai, Linning Xu, Lihan Jiang, Jiangmiao Pang, Mulin Yu†, Bo Dai†

[**Project**](https://city-super.github.io/mvcolight/) [**Paper**](https://arxiv.org/pdf/2505.21483)
- We introduce MV-CoLight, a two-stage framework for illumination-consistent object compositing in both 2D images and 3D scenes.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arxiv 2025</div><img src='images/HaloGS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[HaloGS: Loose Coupling of Compact Geometry and Gaussian Splats for 3D Scenes](https://arxiv.org/abs/2505.20267)

Changjian Jiang*, **Kerui Ren\***, Linning Xu, Jiong Chen, Jiangmiao Pang, Yu Zhang, Bo Dai, Mulin Yu†

[**Project**](https://city-super.github.io/halogs/) [**Paper**](https://arxiv.org/pdf/2505.20267)
- We introduce HaloGS, a dual-representation that loosely couples triangles for geometry with Gaussians for appearance, enabling high-fidelity rendering with compact geometry.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RSS 2025</div><img src='images/RoboSplat.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Novel Demonstration Generation with Gaussian Splatting Enables Robust One-Shot Manipulation](https://www.roboticsproceedings.org/rss21/p146.pdf)

Sizhe Yang*, Wenye Yu*, Jia Zeng, Jun Lv, **Kerui Ren**, Cewu Lu, Dahua Lin, Jiangmiao Pang†

[**Project**](https://yangsizhe.github.io/robosplat/) [**Code**](https://github.com/OpenRobotLab/RoboSplat) [**Paper**](https://www.roboticsproceedings.org/rss21/p146.pdf)
- We introduce RoboSplat, a framework that leverages 3D Gaussian Splatting (3DGS) to generate novel demonstrations for RGB-based policy learning.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/HorizonGS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Horizon-GS: Unified 3D Gaussian Splatting for Large-Scale Aerial-to-Ground Scenes](https://openaccess.thecvf.com/content/CVPR2025/html/Jiang_Horizon-GS_Unified_3D_Gaussian_Splatting_for_Large-Scale_Aerial-to-Ground_Scenes_CVPR_2025_paper.html)

Lihan Jiang*, **Kerui Ren\***, Mulin Yu, Linning Xu, Junting Dong, Tao Lu, Feng Zhao, Dahua Lin, Bo Dai†

[**Project**](https://city-super.github.io/horizon-gs/) [**Code**](https://github.com/OpenRobotLab/HorizonGS) [**Paper**](https://openaccess.thecvf.com/content/CVPR2025/papers/Jiang_Horizon-GS_Unified_3D_Gaussian_Splatting_for_Large-Scale_Aerial-to-Ground_Scenes_CVPR_2025_paper.pdf)
- We introduce Horizon-GS, tackles the unified reconstruction and rendering for aerial and street views with a new training strategy, overcoming viewpoint discrepancies to generate high-fidelity scenes.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arxiv 2025</div><img src='images/BootStrap.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Bootstrap-GS: Self-Supervised Augmentation for High-Fidelity Gaussian Splatting](https://arxiv.org/abs/2404.18669)

Yifei Gao*, **Kerui Ren\***, Jie Ou, Lei Wang, Jiaji Wu, Jun Cheng

[**Code**](https://github.com/yileijin/Bootstrap-GS) [**Paper**](https://arxiv.org/pdf/2404.18669)
- We introduce a bootstrapping framework that generates pseudo-ground truth data from novel viewpoints compatible with the original training set and feeds it back into training, which reduces artifacts, improves metrics, and is adaptable to other Gaussian-based methods.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arxiv 2025</div><img src='images/PayAtten.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Pay Attention to What You Need](https://arxiv.org/abs/2307.13365)

Yifei Gao, Shaohong Chen, Lei Wang, Ruiting Dai, Ziyun Zhang, **Kerui Ren**, Jiaji Wu, Jun Cheng

[**Code**](https://github.com/yileijin/PayAttn) [**Paper**](https://arxiv.org/pdf/2307.13365)
- We propose Scaled ReAttention (SRA), a lightweight method that boosts LLMs' long-context understanding without fine-tuning or retraining.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI 2025</div><img src='images/OctreeGS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Octree-GS: Towards Consistent Real-time Rendering with LOD-Structured 3D Gaussians](https://ieeexplore.ieee.org/document/10993308)

**Kerui Ren\***, Lihan Jiang*, Tao Lu, Mulin Yu, Linning Xu, Zhangkai Ni, Bo Dai†

[**Project**](https://city-super.github.io/octree-gs/) [**Code**](https://github.com/city-super/Octree-GS) [**Paper**](https://arxiv.org/pdf/2403.17898)
- We introduce Octree-GS, featuring an LOD-structured 3D Gaussian approach supporting level-of-detail decomposition for scene representation that contributes to the final rendering results.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCV 2025</div><img src='images/SMHDR.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Semantic Masking with Curriculum Learning for Robust HDR Image Reconstruction](https://link.springer.com/article/10.1007/s11263-025-02504-5?utm_source=rct_congratemailt)

Zhangkai Ni, Yang Zhang, **Kerui Ren**, Wenhan Yang†, Hanli Wang†, Sam Kwong

[**Code**](https://github.com/eezkni/SMHDR)
- We propose a novel SAM-guided MIM for HDR reconstruction (SMHDR). The combination of curriculum learning strategy and masked image modeling bridges the gap between pixel fitting and semantic understanding, which successfully turns the knowledge of SAM into the intrinsic understanding of the quality issues of HDR images.
</div>
</div>

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Educations
- *2024.09 - present*, Ph.D. in Information and Communication Engineering, Shanghai Jiao Tong University
- *20W0.09 - 2024.07*, B.S. in Computer Science and Technology, Tongji University

# 💬 Community Services

Reviewer

- SIGGRAPH Asia 25

# 💻 Internships
- *2023.11 - present*, [Shanghai Artificial Intelligence Laboratory](https://www.shlab.org.cn/), Shanghai, China.