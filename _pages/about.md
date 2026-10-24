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

Yijun Shen (沈逸骏) is a master's student at [East China Normal University (ECNU)](https://www.ecnu.edu.cn/), advised by [Prof. Kai Zhang](https://faculty.ecnu.edu.cn/_s16/zk2/main.psp). He is currently a Research Intern at the **Beijing Academy of Artificial Intelligence (BAAI)**, working on embodied agents and robotic manipulation. He received his B.Eng. degree from Hohai University in 2025, where he worked with [Prof. Fan Liu](https://cies.hhu.edu.cn/2024/0521/c21613a280137/page.htm). His research interests include **Embodied Agents, World Models, VLA, and Long-horizon Task Planning**. Originally from Shanghai, he enjoys badminton and action games outside of research.

# 🔍Research Interests
- **Embodied Agents <span class="research-amp">&amp;</span> Long-horizon Planning**
- **World Models**
- **Vision-Language-Action (VLA) Models**

# 🔥 News
- *2026.05*: &nbsp; "Reward Prediction with Factorized World States" was accepted to ICML 2026 Workshop LM4Plan (Oral). 🎉🎉
- *2025.08*: &nbsp; "Chain-of-Talkers (CoTalk): Fast Human Annotation of Dense Image Captions," was accepted to EMNLP 2025. 🎉🎉
- *2025.03*: &nbsp; "The Intelligent Audit Platform," successfully completed its pilot phase and was officially deployed at the finance department of Spring Airlines. 🎉🎉
- *2024.08*: &nbsp; As team leader, our project "E Mark: Intelligent Marking Platform" won the Second Prize in the National Computer Design Competition and the Third Prize in the National Service Outsourcing Innovation and Entrepreneurship Competition. 🎉🎉
- *2024.06*: &nbsp; Having been awarded the "Ten Outstanding and One Hundred Excellent Students" title (Top 100 university-wide). 🎓🎓
- *2023.09*: &nbsp; "State index for interpreting the state-dependent behavior of granular soil: A review," was accepted to Archives of Computational Methods in Engineering (IF 9.7)! 🎉🎉

# 📖 Educations
- *2025.09 - present*, M.S. College of Computer Science and Technology, East China Normal University, supervised by Prof. Kai Zhang.
- *2021.08 - 2025.07*, B.S. at College of Artificial Intelligence and Automation, Hohai University, supervised by Prof. Fan Liu.

# 💻 Internships
- *2026.07 – Present*, Research Intern, Embodied Intelligence Research Department, **Beijing Academy of Artificial Intelligence (BAAI)**.
- *2024.10 – 2025.03*, Algorithm Intern, **Spring Airlines**, under the supervision of Dr. Zhenya Lin.


# 📝 Selected Publications 

\* Equal Contribution

<div class='paper-box publication-entry' id='paper-2610-29702'>
<div class='paper-box-image'>
<a class="publication-figure" href="images/causground-method-cropped.png" target="_blank" rel="noopener" title="Open full-resolution figure" aria-label="Open full-resolution CausGround method overview">
<img src="images/causground-method-cropped.png" alt="CausGround method overview" width="3400" height="1613" loading="lazy" decoding="async">
</a>
</div>
<div class='paper-box-text' markdown="1">

[CausGround: Causal Interaction Grounding for Adaptive Embodied Planning](https://arxiv.org/abs/2610.29702)

**Yijun Shen**, Diqi He, Jinbang Guo, Wanyue Zhang, Jiaming Mi, Huan Yang, Zhongyuan Wang, Zhiwei Yu, Kai Zhang.

<div class="badge">arXiv 2026</div>

[[**Project Page**]](https://causground.github.io/) [[**Code**]](https://github.com/Intelligent-Interaction/CausGround) [[**X**]](https://x.com/bui_thanh64689/status/2113970576008282485)

- We introduce CausGround, which grounds reusable action preconditions and effects from interaction experience in the current world state, enabling adaptive, training-free long-horizon embodied planning.

</div>
</div>

<div class='paper-box publication-entry' id='paper-2610-27914'>
<div class='paper-box-image'>
<a class="publication-figure" href="images/configwm-method-cropped.png" target="_blank" rel="noopener" title="Open full-resolution figure" aria-label="Open full-resolution ConfigWM method overview">
<img src="images/configwm-method-cropped.png" alt="ConfigWM method overview" width="3400" height="782" loading="lazy" decoding="async">
</a>
</div>
<div class='paper-box-text' markdown="1">

[World Models with Configurable Perception](https://arxiv.org/abs/2610.27914)

**Yijun Shen**\*, Delong Chen\*, Xianming Hu, Kai Zhang, Pascale Fung.

<div class="badge">arXiv 2026</div>

[[**Project Page**]](https://configwm.github.io/) [[**Code**]](https://github.com/yijunshens/ConfigWM) [[**X**]](https://x.com/bui_thanh64689/status/2113170728153649168)

- We introduce ConfigWM, a world model with configurable perception that learns task-relevant visual representations for planning in noisy worlds.

</div>
</div>

<div class='paper-box publication-entry' id='paper-2603-09400'>
<div class='paper-box-image'>
<a class="publication-figure" href="images/statefactory.png" target="_blank" rel="noopener" title="Open full-resolution figure" aria-label="Open full-resolution StateFactory">
<img src="images/statefactory.png" alt="StateFactory" width="3593" height="825" loading="lazy" decoding="async">
</a>
</div>
<div class='paper-box-text' markdown="1">

[Reward Prediction with Factorized World States](https://arxiv.org/abs/2603.09400)

**Yijun Shen**\*, Delong Chen\*, Xianming Hu, Jiaming Mi, Hongbo Zhao, Kai Zhang, Pascale Fung.

<div class="badge">ICML 2026 Workshop LM4Plan (Oral)</div>

[[**Project Page**]](https://statefactory.github.io/) [[**Code**]](https://github.com/yijunshens/StateFactory) [[**X**]](https://x.com/Delong0_0/status/2031669604695576715)

- We introduce StateFactory, a factorized representation method that transforms unstructured observations into a hierarchical object-attribute structure for robust zero-shot reward prediction.

</div>
</div>

<div class='paper-box publication-entry' id='paper-2505-22627'>
<div class='paper-box-image'>
<a class="publication-figure" href="images/CoTalk.jpg" target="_blank" rel="noopener" title="Open full-resolution figure" aria-label="Open full-resolution CoTalk">
<img src="images/CoTalk.jpg" alt="CoTalk" width="985" height="372" loading="lazy" decoding="async">
</a>
</div>
<div class='paper-box-text' markdown="1">

[Chain-of-Talkers (CoTalk): Fast Human Annotation of Dense Image Captions](https://arxiv.org/abs/2505.22627)

**Yijun Shen**\*, Delong Chen\*, Fan Liu\*, Xingyu Wang, Chuanyi Zhang, Liang Yao, Yuhui Zheng.

<div class="badge">EMNLP 2025</div>

[[**Code**]](https://github.com/YiJunShenS/CoTalk)

- We propose an efficient image caption annotation method, which is a sequential cross modal input-output annotation framework, CoTalk.

</div>
</div>

---

# 👥 Co-authors

Prof. [Kai Zhang](https://faculty.ecnu.edu.cn/_s16/zk2/main.psp), Prof. [Fan Liu](https://cies.hhu.edu.cn/2024/0521/c21613a280137/page.htm), [Delong Chen](https://chendelong.world/), [Liang Yao](https://1e12leon.top/), [Xingyu Wang](https://multimodality.group/author/%E7%8E%8B%E5%85%B4%E5%AE%87/)

# 🏆 Competitions

- 2025, bronze medal, Kaggle —— CIBMTR - Equity in post-HCT Survival Predictions
- 2024, Second Prize, Final of National Computer Design Competition \| 中国大学生计算机设计大赛全国总决赛二等奖
- 2024, Third Prize, Final of National Service Outsourcing Innovation and Entrepreneurship Competition \| 中国大学生服务外包创新创业大赛总决赛三等奖
- 2023, Second Prize, Final of Global Campus Artificial Intelligence Algorithm Elite Competition \| 全球校园人工智能算法精英大赛全国总决赛二等奖
- 2023, Honorable Winner, The Mathematical Contest in Modeling (MCM) \| 美国大学生数学建模大赛 Meritorious Winner

# 🎖 Honors and Awards

- 2025, Outstanding Undergraduate Thesis, Hohai University \| 河海大学优秀本科毕业论文
- 2024, "Ten Outstanding and One Hundred Excellent Students" Award, Hohai University  \| 河海大学海韵风华十杰百佳”优秀学生
- 2024, Outstanding Communist Youth League Cadre, Hohai University  \| 河海大学优秀共青团干部
- 2022, 2023, Merit Student, Hohai University  \| 河海大学优秀学生标兵
- 2023, 2025, Outstanding Student Leader, Hohai University  \| 河海大学优秀学生干部
- 2021-2025, Outstanding Undergraduate Student Scholarship, Hohai University  \| 河海大学优秀学生奖学金
