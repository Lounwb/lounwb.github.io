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

I am a graduate student in Computer Science at the University of Electronic Science and Technology of China (UESTC), supervised by <a href="https://scholar.google.com/citations?user=-bk1CrcAAAAJ"> Prof. Xiaofeng Zhu</a>. I received my Bachelor's degree from UESTC in 2025.

My research interests include Few-Shot Learning, Large Language Models (LLMs), and Vision-Language Models (VLMs).


# 🔥 News
- *2025.09*: &nbsp;🌟🌟 I will go to UESTC to enjoy master life.
- *2024.08*: &nbsp;🎉🎉 One paper accepted by Applied Intelligence!

# 📝 Publications 

<!-- Enhancing Few-Shot Out-of-Distribution Detection via the Refinement of Foreground and Background -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2025</div><img src='images/fobor.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Enhancing Few-Shot Out-of-Distribution Detection via the Refinement of Foreground and Background](https://arxiv.org/pdf/2509.17905)

**Tianyu Li**, Songyue Cai, Zongqian Wu, Ping Hu, Xiaofeng Zhu


CLIP-based foreground-background (FG-BG) decomposition enhances few-shot OOD detection, yet existing methods suffer from uniform background suppression and the neglect of confusable foreground patches that mislead training. To address this, we propose a plug-and-play framework featuring Adaptive Background Suppression to weight patch importance and Confusable Foreground Rectification to handle semantic ambiguity. Extensive experiments demonstrate that our approach significantly improves the performance of existing FG-BG decomposition methods.
</div>
</div>

<!-- Mitigating Strategy-Selection Bias in Reasoning for More Effective Test-Time Scaling -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2025</div><img src='images/Uniform-TTS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Mitigating Strategy-Selection Bias in Reasoning for More Effective Test-Time Scaling](https://arxiv.org/pdf/2509.17905)

Zongqian Wu, Baoduo Xu, **Tianyu Li**, Zhu Sun, Xiaofeng Zhu<sup>\*</sup>, Lei Feng<sup>\*</sup>


Test-time scaling (TTS) improves LLM performance by aggregating diverse paths, yet existing research overlooks the critical issue of strategy selection bias, where models favor certain strategies while neglecting valid alternatives. We present a theoretical analysis revealing how this bias undermines scaling effectiveness and introduce TTS-Uniform, a framework designed to mitigate it.
</div>
</div>

<!-- Is Depth All You Need? An Exploration of Iterative Reasoning in LLMs -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2025</div><img src='images/is_depth.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Is Depth All You Need? An Exploration of Iterative Reasoning in LLMsg](https://arxiv.org/abs/2502.10858)

Zongqian Wu, **Tianyu Li**, Baoduo Xu, Jiaying Yang, Mengmeng Zhan, Xiaofeng Zhu, Lei Feng<sup>\*</sup>, Lei Feng<sup>\*</sup>


Deep iterative chain-of-thought (CoT) reasoning faces challenges in ensuring continual improvement and determining stopping criteria. In this paper, we demonstrate that breadth reasoning—increasing the diversity of initial reasoning paths—can effectively circumvent the need for iterative refinement by achieving comparable or superior performance. To address the limited diversity of existing approaches like self-consistency, we propose integrating contextual exploration with reduced sampling randomness, a method that significantly outperforms deep iterative reasoning.
</div>
</div>

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

# 🎖 Honors and Awards
- *2024.12*: Xiaomi Scholarship.
- *2024.05*: West region third prize in 2023 Competition of Service Outsourcing and Entrepreneurship Innovation.
- *2023.12*: Excellent Student Scholarship, TCL scholarship, Yesun scholarship.
- *2023.08*: National third prize in 2022 China Software Cup College Student Software Design Competition.
- *2022.12*: Excellent Student Scholarship.

# 📖 Educations
- *2025.09 - Now **(Master)***: UESTC <img src="images/favicon_usetc.png" alt="11" style="width: 30px; height: 30px;" />, Guiding Instructor: <a href="https://scholar.google.com/citations?user=-bk1CrcAAAAJ"> Prof. Xiaofeng Zhu</a>
- *2021.09 - 2025.06 **(Bachelor)***: UESTC <img src="images/favicon_usetc.png" alt="11" style="width: 30px; height: 30px;" />, Software Engineering.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2025.04 - 2025.09*, [Bytedance](https://www.bytedance.com/en/) <img src="images/bytedance_2.png" alt="ByteDance" style="width: auto; height: 30px;" />, China.