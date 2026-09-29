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

I am a third-year PhD candidate jointly supervised by Shanghai Jiao Tong University and Shanghai Artificial Intelligence Laboratory, under the primary guidance of [**Prof. Bo Dai**](https://scholar.google.com/citations?user=KNWTvgEAAAAJ). Currently, I am also a research intern at the Physical Intelligence Center of Shanghai AI Lab, co-advised by [**Dr. Mulin Yu**](https://mulinyu.github.io/) and [**Dr. Tao Lu**](https://inspirelt.github.io/). Prior to my doctoral studies, I received my Bachelor of Engineering degree from Tongji University, where I conducted research on HDR reconstruction for dynamic scenes under the supervision of [**Prof. Zhangkai Ni**](https://eezkni.github.io/).

My research interests lie in agentic robotics and spatial intelligence. I have published papers in top-tier computer vision conferences and journals including CVPR, NeurIPS, SIGGRAPH, ICLR, RSS, TPAMI, IJCV and TOG, with my publications accumulating 800+ Google Scholar citations.

# 🔥 News
- *2026.09*: &nbsp;🎉 We open-sourced Real2Gym, a unified Real2Sim2Real framework that couples physics-verified environment synthesis with agentic skill accumulation.
- *2026.09*: &nbsp;🎉 Our PLANING on On-the-fly Reconstruction was accepted to NeurIPS 2026.
- *2026.07*: &nbsp;🎉 Our M3 on On-the-fly Reconstruction was accepted to SIGGRAPH Asia 2026.
- *2026.05*: &nbsp;🎉 One paper on Real-to-Sim Neural Simulator was accepted to ICML 2026.
- *2026.04*: &nbsp;🎉 One paper on Physically-based Light Transport was accepted to SIGGRAPH 2026.
- *2026.01*: &nbsp;🎉 Our ARTDECO on On-the-fly Reconstruction was accepted to ICLR 2026.
- *2025.09*: &nbsp;🎉 Our MV-CoLight on Multi-view Object Compositing was accepted to NeurIPS 2025.
- *2025.08*: &nbsp;🎉 One paper on Unposed Novel View Synthesis was accepted to SIGGRAPH Asia 2025 (ACM TOG).
- *2025.06*: &nbsp;🎉 Our SMHDR on Multi-view HDR Reconstruction was accepted to IJCV 2025.
- *2025.05*: &nbsp;🎉 Our Octree-GS on LOD-Structured 3D Gaussians was accepted to TPAMI 2025.
- *2025.04*: &nbsp;🎉 One paper on One-Shot Manipulation was accepted to RSS 2025.
- *2025.02*: &nbsp;🎉 Our Horizon-GS on Aerial-to-Ground Scene Reconstruction was accepted to CVPR 2025.
- *2024.07*: &nbsp;🎓 Graduated from Tongji University.

# 📝 Publications 

(†: corresponding author; * :equal contribution)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arxiv 2026</div><img src='images/Real2Gym.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Real2Gym: Building Gyms from Videos, \\ Bringing Skills to Robots]()

**Kerui Ren\***, Yingxiang Xu\*, Kaiwen Song, Lingning Xu, Bo Dai, Mulin Yu†, Tao Lu†

[**Project**](https://real2gym.github.io/) [**Code**](https://github.com/real2gym/Real2Gym) [**Paper**](https://github.com/real2gym/Real2Gym/tree/main/paper/Real2Gym.pdf)
- We introduce Real2Gym, an agentic Real2Sim2Real framework that turns human and robot demonstrations into interactive simulation gyms and brings skills acquired in simulation to physical robots.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arxiv 2026</div><img src='images/InfiniHand.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[InfiniHand: Streaming World-Space Hand Motion Estimation from Egocentric Video](https://arxiv.org/abs/2609.35743)

**Kerui Ren**, Kaiwen Song, Weiguang Zhao, Yuxi Wang, Yufei Liu, Bo Dai, Haoyu Guo, Chunhua Shen, Mulin Yu†, Tao Lu†, Junting Dong

[**Project**](https://infinihand.github.io/) [**Code**](https://github.com/infinihand/InfiniHand) [**Paper**](https://arxiv.org/pdf/2609.35743)
- we present InfiniHand, an end-to-end streaming feed-forward framework that jointly estimates MANO parameters, camera trajectories, and hand locations directly from uncalibrated egocentric video.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">technical report</div><img src='images/InternW0.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[InternW0-Δ: A World Action Model Bridging Predictive Dynamics and Actions with 20K+ Hours of Open Data](https://arxiv.org/abs/2609.31394)

Physical Intelligence Team

[**Project**](https://internrobotics.github.io/InternW0-Delta/) [**Code**](https://github.com/InternRobotics/InternW0-Delta) 
[**Paper**](https://arxiv.org/pdf/2609.31394)
- We introduce InternW0-Δ, a unified WAM pretrained on a heterogeneous corpus that outperforms prior methods across simulation benchmarks and real-robot platforms.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arxiv 2026</div><img src='images/GeoVerse.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[GeoVerse: World-Consistent Novel View Synthesis in Geometric Latent Space](https://arxiv.org/abs/2609.35734)

**Kerui Ren**, Tao Lu, Linning Xu, Changjian Jiang, Hunag Mu, Chunhua Shen, Mulin Yu†, Bo Dai†

[**Project**](https://geoverse-nvs.github.io/)  [**Code**](https://github.com/geoverse-nvs/GeoVerse) [**Paper**](https://arxiv.org/pdf/2609.35734)
- We propose GeoVerse, a framework that synthesizes world-consistent novel views by performing generation within the geometric latent space of a pretrained 3D foundation model and injecting appearance priors from a video generative model.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arxiv 2026</div><img src='images/Mirage.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MIRAGE: Metric Inference and Reliability-Aware Gaussian Estimation from Feed-Forward Vision]()

Xinzhe Wang, Changjian Jiang, Kaiwen Song, Xudong Li, **Kerui Ren**, Ran Yi, Lizhuang Ma, Chunhua Shen, Linning Xu, Tao Lu, Mulin Yu†

- We propose MIRAGE, which anchors feed-forward visual geometry to LiDAR--IMU metric motion and regulates online pose corrections according to correspondence support and cross-modal agreement, jointly enabling accurate metric pose estimation and high-fidelity Gaussian reconstruction.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arxiv 2026</div><img src='images/AquFlow.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AquaFlow: A Monocular Gaussian Splatting SLAM for Underwater Streaming Reconstruction](https://arxiv.org/abs/2608.22906)

Yingxiang Xu\*, **Kerui Ren\***, Wenqi Guo, Changjian Jiang, Tao Lu, Linning Xu, Mulin Yu†

[**Paper**](https://arxiv.org/pdf/2608.22906)
- AquaFlow is a monocular Gaussian Splatting SLAM framework powered by foundation and optical models for high-fidelity underwater reconstruction.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGGRAPH Asia 2026</div><img src='images/M3.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[M³: Dense Matching Meets Multi-View Foundation Models for Monocular Gaussian Splatting SLAM](https://arxiv.org/abs/2603.16844)

**Kerui Ren**, Guanghao Li, Changjian Jiang, Yingxiang Xu, Tao Lu, Linning Xu, Junting Dong, Jiangmiao Pang, Mulin Yu†, Bo Dai†

[**Project**](https://city-super.github.io/M3/) [**Code**](https://github.com/InternRobotics/M3) [**Paper**](https://arxiv.org/pdf/2603.16844)
- M³ is a Monocular Gaussian Splatting SLAM with a Multi-view foundation model for dense Matching.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2026</div><img src='images/SoMA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SoMA: A Real-to-Sim Neural Simulator for Robotic Soft-body Manipulation](https://arxiv.org/abs/2602.02402)

Mu Huang, Hui Wang, **Kerui Ren**, Linning Xu, Yunsong Zhou, Mulin Yu, Bo Dai, Jiangmiao Pang

[**Project**](https://city-super.github.io/SoMA/) [**Code**](https://github.com/Wrioste/SoMA) [**Paper**](https://arxiv.org/pdf/2601.22046)
- SoMA is a Gaussian splat neural simulator that models deformable object dynamics from real-world robot manipulation, enabling action-conditioned, stable long-horizon simulation with high-fidelity, multi-view–consistent rendering.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGGRAPH 2026</div><img src='images/EAGPT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[EAG-PT: Emission-Aware Gaussians and Path Tracing for Indoor Scene Reconstruction and Editing](https://arxiv.org/abs/2601.23065)

Xijie Yang, Mulin Yu, Changjian Jiang, **Kerui Ren**, Tao Lu, Jiangmiao Pang, Dahua Lin, Bo Dai, Linning Xu

[**Paper**](https://arxiv.org/pdf/2601.23065)
- Emission-Aware Gaussians and Path Tracing (EAG-PT), aiming for physically based light transport with a unified 2D Gaussian representation.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2026</div><img src='images/PLANING.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PLANING: A Loosely Coupled Triangle-Gaussian Framework for Streaming 3D Reconstruction](https://arxiv.org/abs/2601.22046)

Changjian Jiang\*, **Kerui Ren\***, Xudong Li, Kaiwen Song, Guanghao Li, Linning Xu, Tao Lu, Junting Dong, Yu Zhang†, Bo Dai, Mulin Yu†

[**Project**](https://city-super.github.io/PLANING/) [**Code**](https://github.com/InternRobotics/PLANING) [**Paper**](https://arxiv.org/pdf/2601.22046)
- PLANING introduces a loosely coupled triangle-Gaussian representation and a monocular streaming framework that jointly achieves accurate geometry, high-fidelity rendering, and efficient planar abstraction for embodied AI applications.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/ARTDECO.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ARTDECO: Towards Efficient and High-Fidelity On-the-Fly 3D Reconstruction with Structured Scene Representation](https://arxiv.org/abs/2510.08551)

Guanghao Li\*, **Kerui Ren\***, Linning Xu, Zhewen Zheng, Changjian Jiang, Xin Gao, Bo Dai, Jian Pu†, Mulin Yu†, Jiangmiao Pang

[**Project**](https://city-super.github.io/artdeco/) [**Code**](https://github.com/InternRobotics/ARTDECO) [**Paper**](https://arxiv.org/pdf/2510.08551)
- ARTDECO unifies 3D foundation priors with structured scene representations, enabling robust and generalizable 3D reconstruction of diverse real-world scenes using only monocular video.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGGRAPH Asia 2025 (ACM TOG)</div><img src='images/AnySplat.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AnySplat: Feed-forward 3D Gaussian Splatting from Unconstrained Views](https://arxiv.org/abs/2505.23716)

Lihan Jiang\*, Yucheng Mao\*, Linning Xu, Tao Lu, **Kerui Ren**, Yichen Jin, Xudong Xu, Mulin Yu, Jiangmiao Pang, Feng Zhao†, Dahua Lin, Bo Dai†

[**Project**](https://city-super.github.io/anysplat/) [**Code**](https://github.com/OpenRobotLab/AnySplat) [**Paper**](https://arxiv.org/pdf/2505.23716)
- We introduce AnySplat, a feed‑forward network for novel‑view synthesis from uncalibrated image collections in both sparse‑ and dense‑view scenarios.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='images/MVCoLight.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MV-CoLight: Efficient Object Compositing with Consistent Lighting and Shadow Generation](https://arxiv.org/abs/2505.21483)

**Kerui Ren**, Jiayang Bai, Linning Xu, Lihan Jiang, Jiangmiao Pang, Mulin Yu†, Bo Dai†

[**Project**](https://city-super.github.io/mvcolight/) [**Paper**](https://arxiv.org/pdf/2505.21483)
- We introduce MV-CoLight, a two-stage framework for illumination-consistent object compositing in both 2D images and 3D scenes.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISPRS 2026</div><img src='images/HaloGS.png' alt="sym" width="100%"></div></div>
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

# 📖 Educations
- *2024.09 - present*, Ph.D. in Information and Communication Engineering, Shanghai Jiao Tong University
- *2020.09 - 2024.07*, B.S. in Computer Science and Technology, Tongji University

# 💬 Community Services

Reviewer

- NeurIPS, SIGGRAPH Asia, SIGGRAPH
- IEEE TPAMI, IEEE TVCG, IEEE TMM, ISPRS

# 💻 Internships
- *2023.11 - present*, [Shanghai Artificial Intelligence Laboratory](https://www.shlab.org.cn/), Shanghai, China.
