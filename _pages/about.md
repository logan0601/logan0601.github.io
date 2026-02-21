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
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@google-scholar-stats/" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/google-scholar-stats/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

Hi there 👋.

I am currently a PhD student in the Department of Computer Science and Technology at Tsinghua University.

My research interest lies in multi-modal generative models, 3D generation, computer graphics. 


# 📖 Education
- *2022.09 - present*, PhD student, Department of Computer Science and Technology, Tsinghua University
- *2018.09 - 2022.06*, B.Sc, Department of Computer Science and Technology, Tsinghua University

# 🔬 Lab
- *2021.09 - Present*, [Graphics and Geometric Computing Group (G2)](https://cg.cs.tsinghua.edu.cn/), Tsinghua University, China

# 📝 Publications 

<a href='https://scholar.google.com/citations?user=xvOPuFcAAAAJ&hl'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/topomesh.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[TopoMesh: High-Fidelity Mesh Autoencoding via Topological Unification](../projects/topomesh/index.html)

**Guan Luo**, Xiu Li, Rui Chen, Xuanyu Yi, Jing Lin, Chia-Hao Chen, Jiahang Liu, Song-Hai Zhang, Jianfeng Zhang

[**Project**](../projects/topomesh/index.html)

-  we introduce TopoMesh, a sparse voxel-based VAE that unifies both GT and predicted meshes under a shared Dual Marching Cubes topological framework. This establishes explicit correspondences at the vertex and face level, allowing us to derive explicit mesh-level supervision signals for topology, vertex positions, and face orientations with clear gradients.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/lafite.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[LaFiTe: A Generative Latent Field for 3D Native Texturing](https://arxiv.org/pdf/2512.04786)

Chia-Hao Chen, Zi-Xin Zou, Yan-Pei Cao, Ze Yuan, **Guan Luo**, Xiaojuan Qi, Ding Liang, Song-Hai Zhang, Yuan-Chen Guo

[**Project**](https://vast-ai-research.github.io/LaFiTe/)

-  We introduce LaFiTe, a framework that addresses this challenge by learning to generate textures as a 3D generative sparse latent color field.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/seed3d.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Seed3D 1.0: From Images to High-Fidelity Simulation-Ready 3D Assets](https://www.seed-3d.net/seed3d.pdf)

Seed3D Team

[**Project**](https://seed.bytedance.com/en/seed3d)

-  We present Seed3D 1.0, a foundation model that generates simulation-ready 3D assets from single images, addressing the scalability challenge while maintaining physics rigor. Unlike existing 3D generation models, our system produces assets with accurate geometry, well-aligned textures, and realistic physically-based materials.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='images/ms3d.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[MS3D: High-Quality 3D Generation via Multi-Scale Representation Modeling](https://openaccess.thecvf.com/content/ICCV2025/papers/Luo_MS3D_High-Quality_3D_Generation_via_Multi-Scale_Representation_Modeling_ICCV_2025_paper.pdf)

**Guan Luo**, Jianfeng Zhang

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=xvOPuFcAAAAJ&citation_for_view=xvOPuFcAAAAJ:Tyk-4Ss8FVUC)

-  we introduce MS3D, a novel multi-scale 3D reconstruction framework. At its core, we introduce a hierarchical structured latent representation for multi-scale modeling, coupled with a multi-scale feature extraction and integration mechanism, which enables progressive reconstruction, effectively decomposing the complex task of detailed geometry reconstruction into a sequence of easier steps.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2024</div><img src='images/gsedit.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[3D Gaussian Editing With A Single Image](https://arxiv.org/pdf/2408.07540)

**Guan Luo**, Tian-Xing Xu, Ying-Tian Liu, Xiao-Xiong Fan, Fang-Lue Zhang, Song-Hai Zhang

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=xvOPuFcAAAAJ&authuser=1&citation_for_view=xvOPuFcAAAAJ:9yKSN-GCB0IC)

-  we introduce a novel single-image-driven 3D scene editing approach based on 3D Gaussian Splatting, enabling intuitive manipulation via directly editing the content on a 2D image plane. Our method learns to optimize the 3D Gaussians to align with an edited version of the image rendered from a user-specified viewpoint of the original scene.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023 Workshop</div><img src='images/threestudio.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Threestudio: A unified framework for 3d content generation](https://cg.cs.tsinghua.edu.cn/threestudio/ICCV2023_AI3DCC_threestudio.pdf)

Yuan-Chen Guo, Ying-Tian Liu, Ruizhi Shao, Christian Laforte, Vikram Voleti, **Guan Luo**, Chia-Hao Chen, Zi-Xin Zou, Chen Wang, Yan-Pei Cao, Song-Hai Zhang

[**Project**](https://github.com/threestudio-project/threestudio)

-   We introduce threestudio, an open-source, unified, and modular framework specifically designed for 3D content generation. This framework extends diffusion-based 2D image generation models to 3D generation guidance while incorporating conditions such as text and images. We delineate the modular architecture and design of each component within threestudio. 
</div>
</div>

# 📖 Notes

[Stochastic Differential Equations and Diffusion Models](../notes/Stochastic_Differential_Equations.pdf)

[Differential Manifolds[Up to Chapter1.2]](../notes/Differential_Manifold.pdf)



<hr />

Last updated: 12/12/2025