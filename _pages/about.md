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

Hi there, I am **Zihao Liu** (Chinese name: 刘子豪), you can call me "Edward". I am currently a Ph.D. student at School of Artificial Intelligence, CUHK-Shenzhen under the supervision of Prof. Feng Yin. I previously received my B.Eng. degree at School of Mechanical Engineering, Tongji University (2021.09-2025.07).

My research focuses on developing next-generation intelligent analytical systems by exploring the intersection of **Spatio-Temporal Modeling**, **Continual Learning**, and **Representation Geometry**. Specifically, I investigate:
- **Spatio-Temporal Dynamics:** Designing architectures that jointly capture multi-scale spatial correlations and long-range temporal dependencies.
- **Continual Learning:** Developing robust mechanisms to overcome catastrophic forgetting, enabling models to adapt to shifting data distributions in real-time.
- **Representation Geometry:** Exploring the intrinsic geometric structures and manifold properties of latent spaces to enhance the interpretability and generalization of deep representations.

My research aims to build foundation models that are not only aware of complex multi-dimensional dependencies but also capable of evolving in non-stationary environments.
I am always open to collaborations. Please feel free to reach out to me at [my email](zihaoliu1@link.cuhk.edu.cn)!

# 🔥 News
- *2026.08*: &nbsp;🎉 Invited as a peer reviewer for [AAAI 2027](https://aaai.org/conference/aaai/aaai-27/)!
- *2026.06*: &nbsp;🎉 Invited as a peer reviewer for [MLSP 2026](https://mlsp26.ieeesps.org/)!
- *2025.11*: &nbsp;🎉 Invited as a peer reviewer for [ICASSP 2026](https://2026.ieeeicassp.org/)!
- *2025.08*: &nbsp;🎉 Join the [BLSP Group](https://blsp-group.github.io/) and become a member of it!
- *2024.05*: &nbsp;🎉 Won the title of "Honarable Mention" in "Mathematical Contest in Modeling".
- *2023.10*: &nbsp;🎉 Won the **1st** prize in the "Chinese Mechanical Engineering Innovation and Creativity Competition".
- *2022.12*: &nbsp;🎉 Won the **2nd** prize in the "Shanghai College Student Engineering Practice and Innovation Ability Competition".

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/spatio_temporal_traffic.png' alt="Spatio-Temporal Traffic Prediction" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Spatio-Temporal Traffic Prediction for Grid-Structured Wireless Network**

Ao Wang, **Zihao Liu**, Juntao Wang, Feng Yin

- A distribution-aware unified spatio-temporal forecasting framework for grid-structured wireless networks, featuring dynamic periodic decomposition, graph-constrained attention, and uncertainty-aware probabilistic prediction.

</div>
</div>

# 🎖️ Honors and Awards
- *2022 & 2023 & 2024*: &nbsp;💰 Repeatedly awarded "Outstanding Student Scholarship" by Tongji University. 
- *2023.10*: &nbsp;🏆 Won the **1st** prize in the "Chinese Mechanical Engineering Innovation and Creativity Competition".
- *2023.09*: &nbsp;🏆 Received the "Integrated Competence" certificate awarded by TÜV Rheinland Industry 4.0 Laboratory Center-China.

# 📖 Educations
- *2025.08 - Present*, Ph.D. in Artificial Intelligence at Chinese University of Hong Kong, Shenzhen. 
- *2021.09 - 2025.07*, B.Eng. in Intelligent Manufacturing Engineering, Tongji University, Shanghai. 

# 💼 Services
- *2026.09 - Present*, Serve as a teaching assistant for [AIE1903, AI Exploration III](https://www.cuhk.edu.cn/en/course/18734).
- *2026.08 - Present*, Serve as a resident tutor at [Eighth College](https://eighth.cuhk.edu.cn/).
- *2025.09 - 2026.01*, Serve as a teaching assistant for [MAT1001, Calculus I](https://www.cuhk.edu.cn/en/course/17708).

# 💻 Internships
- *2024.08 - 2025.05*, Full-time strategic intern as a machine learning engineer in [Bosch Corporate Research Asia Pacific](https://www.bosch.com/research/about-bosch-research/research-locations/), Bosch (China) Investment Ltd., Shanghai.

# 🌍 Visitor Map
<!-- Pageviews Counter -->
<script async type="text/javascript"
        src="https://mapmyvisitors.com/counter.js?d=PUCXUJ9M6q4ZWN_Z-IXMeP7TtfQWchclhG0uvvCDq9E&v=1">
</script>

<!-- Visitor Map (Centered) -->
<div style="width:420px; margin:auto;">
  <script async type='text/javascript' id='mapmyvisitors'
          src='https://mapmyvisitors.com/map.js?cl=080808&w=420&t=n&d=PUCXUJ9M6q4ZWN_Z-IXMeP7TtfQWchclhG0uvvCDq9E&co=ffffff&cmo=3acc3a&cmn=ff5353&ct=808080'>
  </script>
</div>

<!-- Logos Section -->
<style>
.footer-logos {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 28px;            /* 间距，按需调整 */
  margin-top: 14px;
  margin-bottom: 40px;
  flex-wrap: nowrap;    /* 强制一行显示；若要响应式换行改成: wrap */
}

/* 统一视觉高度并限制单个图片最大占用宽度 */
.footer-logos img {
  height: 80px;         /* 统一高度（你可改成 45 / 48 / 60） */
  width: auto; 
  max-width: 240px;     /* 对极宽图（比如 Bosch）生效，防止撑破布局 */
  object-fit: contain;
  display: inline-block;
  vertical-align: middle;
  transition: transform .15s ease, opacity .15s ease;
  opacity: 0.98;
}

.footer-logos img:hover {
  transform: translateY(-4px);
  opacity: 1;
}
</style>

<div class="footer-logos" aria-label="Affiliated logos">
  <img src="{{ site.baseurl }}/images/cuhksz_logo.png" alt="CUHKSZ Logo">
  <img src="{{ site.baseurl }}/images/CUHK-SAI-Logo-02.png" alt="SAI Logo">
  <img src="{{ site.baseurl }}/images/tongji_logo.png" alt="Tongji Logo">
  <img src="{{ site.baseurl }}/images/Bosch_logo.png" alt="Bosch Logo">
</div>
