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

# About Me

I am a master student at the [Learning, Vision and Remote Sensing Laboratory (LEVIR)](https://levir.buaa.edu.cn/) at Beihang University. My research interests include remote sensing image understanding, multimodal learning, adversarial robustness, and diffusion-based image editing.

I am particularly interested in reliable visual generation and editing systems: how models interpret visual evidence, how adversarial perturbations affect this interpretation, and how representation-level constraints can improve robustness.

<div class="profile-links" markdown="1">
[Google Scholar](https://scholar.google.com/citations?user=ijCq9e0AAAAJ&hl=zh-CN){: .btn .btn--primary}
[GitHub](https://github.com/Arknightpzb){: .btn}
[LEVIR Profile](https://levir.buaa.edu.cn/members/index.html){: .btn}
[Email](mailto:20374343@buaa.edu.cn){: .btn}
</div>

# News

- *2026.06*: This homepage is being updated for a public academic profile and GitHub Pages deployment.
- *2025.01*: Our survey paper on physical adversarial attacks against visual deep learning models appeared in the *Journal of Image and Graphics*.
- *2024.05*: Our TGRS paper on physical adversarial camouflage generation for optical remote sensing images was published.

# Research Interests

- Robust diffusion-based image editing and representation stability.
- Physical and digital adversarial robustness for visual recognition and remote sensing systems.
- Remote sensing image understanding, multimodal learning, and RGB-T salient object detection.
- Deepfake image detection, localization, and visual media forensics.

# Selected Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TGRS 2024</div><img src='images/500x300.png' alt="remote sensing adversarial camouflage" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Physical Adversarial Camouflage Generation in Optical Remote Sensing Images](https://ieeexplore.ieee.org/document/10460320)

Wei Chen, Yongyuan Liang, **Zhenbang Peng**, Yueyang Wu, Junjie Yang, Qixiang Ye, Yanyun Qu

*IEEE Transactions on Geoscience and Remote Sensing*, 2024.

- Studies physical adversarial camouflage generation for optical remote sensing images and evaluates robustness against remote sensing object detectors.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JIG 2025</div><img src='images/500x300.png' alt="adversarial robustness survey" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Review of physical adversarial attacks against visual deep learning models](https://www.cjig.cn/en/article/doi/10.11834/jig.240442/)

**Zhenbang Peng**, Wei Chen, Zhen Li, Bin Zeng

*Journal of Image and Graphics*, 2025.

- Surveys physical adversarial attacks against visual deep learning models and discusses attack settings, evaluation, and future research directions.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Remote Sensing</div><img src='images/500x300.png' alt="rgb-t salient object detection" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Cross-Modal Guidance Distillation Network with Transformer for RGB-T Salient Object Detection](https://www.mdpi.com/2072-4292/15/16/3979)

**Zhenbang Peng**, Wei Chen, Yunpeng Xiao, Li Sun, Xiaojun Wu, Zhun Fan

*Remote Sensing*, 2023.

- Explores transformer-based cross-modal guidance distillation for RGB-T salient object detection.
</div>
</div>

More publications can be found on my [Google Scholar profile](https://scholar.google.com/citations?user=ijCq9e0AAAAJ&hl=zh-CN).

# Education

- *M.S.*, Beihang University, LEVIR Lab, Beijing, China.

# Contact

I am open to research discussions and collaboration in robust visual generation, adversarial robustness, and remote sensing image understanding.

- Email: [20374343@buaa.edu.cn](mailto:20374343@buaa.edu.cn)
- GitHub: [Arknightpzb](https://github.com/Arknightpzb)
