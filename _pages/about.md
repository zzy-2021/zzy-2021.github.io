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

I am a Ph.D. student in the School of Automation Science and Engineering at **South China University of Technology (SCUT)**, advised by [Prof. Yu Liu](https://www2.scut.edu.cn/automation/). My research interests include **robot perception, 3D vision, SLAM, and large language model (LLM) reasoning**. I focus on developing robust visual localization and mapping algorithms for mobile robots, as well as exploring the integration of multi-modal large models for intelligent systems.

<span class='anchor' id='-news'></span>

# 🔥 News
- *2026.02*: &nbsp;🎉🎉 One paper accepted by **CVPR 2026** (CCF-A)!
- *2025.10*: &nbsp;🎉🎉 Won the **Xinwangda New Energy Technology Innovation Scholarship** at SCUT.
- *2025.10*: &nbsp;🎉 One patent granted: *Visual UAV Trajectory Estimation Method with Co-View Constraints*.
- *2024.05*: &nbsp;🎉 One patent granted: *Binocular Visual Odometry Method with Dynamic Object Detection*.

<span class='anchor' id='-publications'></span>

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AERGS-SLAM: Auto-Exposure-Robust Stereo 3D Gaussian Splatting SLAM](https://openaccess.thecvf.com/content/CVPR2026/papers/Zhou_AERGS-SLAM_Auto-Exposure-Robust_Stereo_3D_Gaussian_Splatting_SLAM_CVPR_2026_paper.pdf)

**Zhiyu Zhou**, Feng Hui, Yu Liu*

*IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2026* (CCF-A)

[**PDF**](https://openaccess.thecvf.com/content/CVPR2026/papers/Zhou_AERGS-SLAM_Auto-Exposure-Robust_Stereo_3D_Gaussian_Splatting_SLAM_CVPR_2026_paper.pdf) \| [**Code**](https://github.com/zzy-2021/AERGS-SLAM)
- Proposes a stereo auto-exposure-robust Gaussian splatting SLAM framework that handles camera auto-exposure variations for reliable localization and photorealistic mapping.

</div>
</div>

- [HBA-VIO: High-Precision Direct Sparse Monocular Visual-Inertial Odometry via Hybrid Bundle Adjustment](), **Zhiyu Zhou**, Han Zhang, Feng Hui, Junyi Wu, Yu Liu*. *IEEE/ASME Transactions on Mechatronics, 2026* (SCI Q1)
- [Visual Localization Using 3D Gaussian Splatting Representation for Mobile Robots with Geometric Feature Correspondences Synthesis](https://doi.org/10.1109/TASE.2025.3601848), **Zhiyu Zhou**, Feng Hui, Xing Li, Yu Liu*. *IEEE Transactions on Automation Science and Engineering, 2025* (SCI Q1)
- [Six-DoF Pose Estimation with Efficient 3-D Gaussian Splatting Representation for Visual Relocalization](https://doi.org/10.1109/TMECH.2024.3507134), **Zhiyu Zhou**, Feng Hui, Yu Liu*. *IEEE/ASME Transactions on Mechatronics, 2025* (SCI Q1)
- [Optical Flow-Based Stereo Visual Odometry with Dynamic Object Detection](https://doi.org/10.1109/TCSS.2022.3205015), Yu Liu, **Zhiyu Zhou**. *IEEE Transactions on Computational Social Systems, 2023* (SCI Q2)
- [Stereo Visual Odometry for Object Segmentation Based on Sparse Optical Flow in Dynamic Scene](https://doi.org/10.23919/CCC55666.2022.9901713), **Zhiyu Zhou**, Yu Liu*. *Chinese Control Conference (CCC), 2022* (EI)

<span class='anchor' id='-patents'></span>

# 📜 Patents

- *2025.10*: Yu Liu, Han Zhang, **Zhiyu Zhou**, Siwen Wu. *Visual UAV Trajectory Estimation Method with Co-View Constraints*. **ZL202411361242.3** (Granted)
- *2024.05*: Yu Liu, **Zhiyu Zhou**, Feng Hui, Chengjun Zhang. *Binocular Visual Odometry Method with Dynamic Object Detection*. **ZL202111263043.5** (Granted)
- Yu Liu, Chengjun Zhang, **Zhiyu Zhou**, Weitao Wang. *Pose Estimation Method for Robot Localization in Low-to-Medium Speed Environments*. **CN202311257356.9** (Published)
- Yu Liu, Feng Hui, **Zhiyu Zhou**, Han Zhang. *LiDAR-Visual-Inertial SLAM Localization Method Fusing Point and Line Features*. **CN202311728894.1** (Published)

<span class='anchor' id='-honors-and-awards'></span>

# 🎖 Honors and Awards
- *2025*: **Xinwangda New Energy Technology Innovation Scholarship**, South China University of Technology
- *2023*: **GAC Scholarship**, South China University of Technology

<span class='anchor' id='-educations'></span>

# 📖 Educations
- *2023.09 - Present*: **Ph.D.** in Electronic Information, South China University of Technology. Advisor: Prof. Yu Liu
- *2020.09 - 2023.06*: **M.Eng.** in Control Science and Engineering, South China University of Technology. Advisor: Prof. Yu Liu
- *2016.09 - 2020.06*: **B.Eng.** in Process Equipment and Control Engineering, North University of China

<span class='anchor' id='-projects'></span>

# 💻 Research Projects

- *2026.01 - Present*: **National Major Scientific Research Instrument Development Project** — *Intelligent Defect Detection Instrument for TGV Advanced Packaging of Chip Substrates* (Grant No. 62433011). Role: Converting multi-source heterogeneous data (defect image attributes, equipment logs, process parameters) into structured text descriptions, and analyzing defect causes using large language models.
- *2021.12 - 2024.11*: **National Key R&D Program** — *Key Technology Development and Demonstration of Vehicle-Grade Solid-State LiDAR for Autonomous Driving* (Grant No. 2021YFB3202200). Role: Developing high-fidelity 3D scene reconstruction algorithms based on LiDAR point clouds, and conducting real-world experiments on mobile robots.
- *2021.07 - 2024.06*: **Guangdong Provincial Key-Area R&D Program** — *Key Technology Development and Industrialization of Intelligent Visual Inspection for Human-Robot Collaboration* (Grant No. 2021B0101200001). Role: Developing visual localization algorithms for inspection scenarios, achieving high-precision pose estimation and spatial modeling of inspection targets.

<span class='anchor' id='-skills'></span>

# 🛠 Skills
- **Programming**: C++, Python, PyTorch
- **Tools & Platforms**: Linux, ROS, Git
- **Research Areas**: Visual SLAM, 3D Gaussian Splatting, Visual Localization, Large Language Models
