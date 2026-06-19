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

I am a Master's student at <a href="https://www.hust.edu.cn/">Huazhong University of Science and Technology</a>, advised by <a href="https://xwcv.github.io/">Prof. Xinggang Wang</a> and <a href="https://eic.hust.edu.cn/professor/liuwenyu/">Prof. Wenyu Liu</a>. I work with the <a href="https://hustvl.github.io/">HUST Vision Lab</a> on Physical AI.

My research explores how intelligent systems can ground perception, reasoning, and action in the physical world. I am particularly interested in developing generalizable models for embodied and driving scenarios, where agents must understand dynamic environments, reason over spatial-temporal context, and make robust decisions under open-world uncertainty.

# News
- *2026.04*: We released UniDriveVLA on arXiv, a unified VLA framework for autonomous driving.
- *2026.06*: One paper was accepted to the European Conference on Computer Vision (ECCV 2026).
- *2026.02*: Two papers were accepted to the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR 2026).
- *2026.01*: ReCogDrive was accepted to the International Conference on Learning Representations (ICLR 2026).
- *2025.02*: One paper on open-vocabulary segmentation was accepted to the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR 2025).

# Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2026</div><img src='images/UniDriveVLA.png' alt="UniDriveVLA overview" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**UniDriveVLA: Unifying Understanding, Perception, and Action Planning for Autonomous Driving**

**Yongkang Li**, Lijun Zhou, Sixu Yan, Bencheng Liao, Tianyi Yan, Kaixin Xiong, Long Chen, Hongwei Xie, Bing Wang, Guang Chen, Hangjun Ye, Wenyu Liu, Haiyang Sun, Xinggang Wang

**arXiv preprint, 2026**

Unified driving VLA model that decouples understanding, perception, and action planning with a Mixture-of-Transformers architecture.

[**Paper**](https://arxiv.org/pdf/2604.02190) \| [**Project**](https://xiaomi-research.github.io/unidrivevla/) \| [![](https://img.shields.io/github/stars/xiaomi-research/unidrivevla?style=social&label=Code Stars)](https://github.com/xiaomi-research/unidrivevla)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/ReCogDrive.png' alt="ReCogDrive overview" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**ReCogDrive: A Reinforced Cognitive Framework for End-to-End Autonomous Driving**

**Yongkang Li<sup>*</sup>**, Kaixin Xiong<sup>*</sup>, Xiangyu Guo, Fang Li, Sixu Yan, Gangwei Xu, Lijun Zhou, Long Chen, Haiyang Sun, Bing Wang, Guang Chen, Hangjun Ye, Wenyu Liu, Xinggang Wang (<sup>*</sup> denotes equal contribution)

**International Conference on Learning Representations, 2026**

Reinforced cognitive framework that aligns VLM-based driving understanding with diffusion planning and reinforcement learning.

[**Paper**](https://arxiv.org/pdf/2506.08052) \| [**OpenReview**](https://openreview.net/forum?id=JoXwhGbuMi) \| [**Project**](https://xiaomi-research.github.io/recogdrive/) \| [![](https://img.shields.io/github/stars/xiaomi-research/recogdrive?style=social&label=Code Stars)](https://github.com/xiaomi-research/recogdrive)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/Mask-Adapter.png' alt="Mask-Adapter overview" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Mask-Adapter: The Devil is in the Masks for Open-Vocabulary Segmentation**

**Yongkang Li<sup>*</sup>**, Tianheng Cheng<sup>*</sup>, Bin Feng, Wenyu Liu, Xinggang Wang (<sup>*</sup> denotes equal contribution)

**IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2025**

Plug-and-play mask adaptation method for improving open-vocabulary segmentation by better aligning proposal masks with vision-language features.

[**Paper**](https://openaccess.thecvf.com/content/CVPR2025/papers/Li_Mask-Adapter_The_Devil_is_in_the_Masks_for_Open-Vocabulary_Segmentation_CVPR_2025_paper.pdf) \| [![](https://img.shields.io/github/stars/hustvl/MaskAdapter?style=social&label=Code Stars)](https://github.com/hustvl/MaskAdapter)

<i class="fas fa-trophy" style="color: #ffd700;"></i> Rank 1st in [Open Vocabulary Segmentation on ADE20K-150](https://paperswithcode.com/sota/open-vocabulary-semantic-segmentation-on-2?p=mask-adapter-the-devil-is-in-the-masks-for) with mIoU=38.2
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2026</div><img src='images/Food-R1.png' alt="Food-R1 overview" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Food-R1: A Unified Multi-Task Food Vision-Language Model with Reinforcement Learning**

Yu Zhu<sup>*</sup>, **Yongkang Li<sup>*</sup>**, Wenjie Zhu, Haoyi Jiang, Wenyu Liu, Wei Yang, Bin Li, Xinggang Wang (<sup>*</sup> denotes equal contribution)

**arXiv preprint, 2026**

Unified food vision-language model trained with multi-task learning, chain-of-thought distillation, and reinforcement fine-tuning for food analysis and calorie reasoning.

[**Paper**](https://arxiv.org/pdf/2606.04986) \| [**Code**](https://github.com/hustvl/Food-R1)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/DriveLaW.png' alt="DriveLaW overview" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**DriveLaW: Unifying Planning and Video Generation in a Latent Driving World**

Tianze Xia<sup>*</sup>, **Yongkang Li<sup>*</sup>**, Lijun Zhou<sup>*</sup>, Jingfeng Yao, Kaixin Xiong, Haiyang Sun, Bing Wang, Kun Ma, Guang Chen, Hangjun Ye, Wenyu Liu, Xinggang Wang (<sup>*</sup> denotes equal contribution)

**IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2026**

Latent driving world model that unifies future video generation and trajectory planning through shared world representations.

[**Paper**](https://arxiv.org/pdf/2512.23421) \| [**Project**](https://wm-research.github.io/DriveLaW/) \| [**Code**](https://github.com/xiaomi-research/drivelaw)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026 Findings</div><img src='images/AD-R1.png' alt="AD-R1 overview" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**AD-R1: Closed-Loop Reinforcement Learning for End-to-End Autonomous Driving with Impartial World Models**

Tianyi Yan, Tao Tang, Xingtai Gui, **Yongkang Li**, Jiasen Zheng, Weiyao Huang, Lingdong Kong, Wencheng Han, Xia Zhou, Xueyang Zhang, Yifei Zhan, Kun Zhan, Cheng-zhong Xu, Jianbing Shen

**IEEE/CVF Conference on Computer Vision and Pattern Recognition Findings, 2026**

Closed-loop reinforcement learning framework that trains an impartial world model to imagine unsafe outcomes and improve autonomous driving policy robustness.

[**Paper**](https://arxiv.org/pdf/2511.20325) \| [**OpenReview**](https://openreview.net/forum?id=IVVtkkoTAF)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2026</div><img src='images/DriveFine.png' alt="DriveFine overview" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**DriveFine: Refining-Augmented Masked Diffusion VLA for Precise and Robust Driving**

Chenxu Dang, Sining Ang, **Yongkang Li**, Haochen Tian, Jie Wang, Guang Li, Hangjun Ye, Jie Ma, Long Chen, Yan Wang

**European Conference on Computer Vision, 2026**

Masked diffusion VLA with refinement experts and hybrid reinforcement learning for precise, robust autonomous driving trajectories.

[**Paper**](https://arxiv.org/pdf/2602.14577) \| [**Code**](https://github.com/MSunDYY/DriveFine)

</div>
</div>

# Honors and Awards
- *2025.06*, Outstanding Graduate of Huazhong University of Science and Technology
- *2024.09*, Huazhong University of Science and Technology Excellence in Learning Scholarship, Science and Technology Innovation Scholarship
- *2024.09*, China National Scholarship
- *2024.06*, MindSpore Open-Source Outstanding Intern
- *2024.05*, Huawei ICT Competition Global Final, Grand Prize
- *2024.05*, Ascend Excellent Developer - Best Contribution Award
- *2024.03*, Huawei ICT Competition National First Prize
- *2023.11*, Ascend AI Innovation Competition, Silver Prize
- *2022.10*, WeiPai Seed Cup Champion, Huazhong University of Science and Technology

# Education
- *2025.09 - Present*, Master's degree, Huazhong University of Science and Technology, Wuhan, China, advised by [Prof. Xinggang Wang](https://xwcv.github.io/) and [Prof. Wenyu Liu](https://eic.hust.edu.cn/professor/liuwenyu/)
- *2021.09 - 2025.06*, Bachelor, Communication and Information Engineering for Exemplary Engineer Education, Huazhong University of Science and Technology, Wuhan, China

# Internships
- *2026.04 - Present*, Research Intern, ByteDance Seed, China.
- *2024.12 - 2026.04*, Research Intern, Xiaomi EV, China.
- *2024.01 - 2024.06*, Research Intern (Remote), MindSpore, China.
