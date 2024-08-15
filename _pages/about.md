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

Hi there 👋.

I am currently a PhD student in the Department of Computer Science and Technology at Tsinghua University.

My research interest lies in 3D generation, computer graphics and computer vision. 


# 📖 Education
- *2022.09 - present*, PhD student, Department of Computer Science and Technology, Tsinghua University
- *2018.09 - 2022.06*, B.Sc, Department of Computer Science and Technology, Tsinghua University

# 🔬 Lab
- *2021.09 - Present*, [Graphics and Geometric Computing Group (G2)](https://cg.cs.tsinghua.edu.cn/), Tsinghua University, China

# 📝 Publications 

<a href='https://scholar.google.com/citations?user=xvOPuFcAAAAJ&hl'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2024</div><img src='images/gsedit.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[3D Gaussian Editing With A Single Image]()

**Guan Luo**, Tian-Xing Xu, Ying-Tian Liu, Xiao-Xiong Fan, Fang-Lue Zhang, Song-Hai Zhang

[**Project**]() <strong><span class='show_paper_citations' data=''></span></strong>
-  we introduce a novel single-image-driven 3D scene editing approach based on 3D Gaussian Splatting, enabling intuitive manipulation via directly editing the content on a 2D image plane. Our method learns to optimize the 3D Gaussians to align with an edited version of the image rendered from a user-specified viewpoint of the original scene.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/pi3d.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Pi3d: Efficient text-to-3d generation with pseudo-image diffusion](https://openaccess.thecvf.com/content/CVPR2024/papers/Liu_PI3D_Efficient_Text-to-3D_Generation_with_Pseudo-Image_Diffusion_CVPR_2024_paper.pdf)

Ying-Tian Liu, **Guan Luo**, Heyi Sun, Yuan-Chen Guo, Wei Yin, Song-Hai Zhang

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=xvOPuFcAAAAJ&citation_for_view=xvOPuFcAAAAJ:u-x6o8ySG0sC) <strong><span class='show_paper_citations' data='xvOPuFcAAAAJ:u-x6o8ySG0sC'></span></strong>
-  We present PI3D, a framework that fully leverages the pre-trained text-to-image diffusion models’ ability to generate high-quality 3D shapes from text prompts in minutes. The core idea is to connect the 2D and 3D domains by representing a 3D shape as a set of Pseudo RGB Images. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023 Workshop</div><img src='images/threestudio.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Threestudio: A unified framework for 3d content generation](https://github.com/threestudio-project/threestudio)

Yuan-Chen Guo, Ying-Tian Liu, Ruizhi Shao, Christian Laforte, Vikram Voleti, **Guan Luo**, Chia-Hao Chen, Zi-Xin Zou, Chen Wang, Yan-Pei Cao, Song-Hai Zhang

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=xvOPuFcAAAAJ&authuser=1&citation_for_view=xvOPuFcAAAAJ:u5HHmVD_uO8C) <strong><span class='show_paper_citations' data='xvOPuFcAAAAJ:u5HHmVD_uO8C'></span></strong>

-   We introduce threestudio, an open-source, unified, and modular framework specifically designed for 3D content generation. This framework extends diffusion-based 2D image generation models to 3D generation guidance while incorporating conditions such as text and images. We delineate the modular architecture and design of each component within threestudio. 
</div>
</div>

# 📖 Notes

[Stochastic Differential Equations](../notes/Stochastic_Differential_Equations.pdf)



<hr />

Last updated: 24/07/2024