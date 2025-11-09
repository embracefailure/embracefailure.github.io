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

<h1>
  😄 Hi
  <!-- <img src="https://profile-counter.glitch.me/embracefailure/count.svg"/>
  visitor! -->
</h1>

I'm Timmy Wen

I build bridges between AI and applications.

My journey at Microsoft and Tesla taught me valuable lessons:

1. Data is fundamental for intelligence
2. Evaluation is important but lack attention
3. Keep an open mind and never stop growing

One more thing, my favorite color is <span style="color: #8C1515">Cardinal Red</span> <img src="https://upload.wikimedia.org/wikipedia/commons/4/4b/Stanford_Cardinal_logo.svg" width="15" height="15" style="vertical-align: middle;"> what about you?

<span class="anchor" id="-magic-moments"></span>

<!--My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).-->


# 🔥 Magic Moments
- *2024.10*: &nbsp;🎉🎉 I was invited to attend the GitHub Universe 2024 conference in San Francisco. Microsoft and GitHub gave me full reimbursement.

<!-- - *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

<span class="anchor" id="-publications"></span>

# 📝 Publications 
<div class="publications-section">
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Arxiv</div>
      <img src='/images/arxiv.png' alt="sym" width="100%">
    </div>
  </div>
<div class='paper-box-text' markdown="1">

[Fully Exploiting Vision Foundation Model's Profound Prior Knowledge for Generalizable RGB-Depth Driving Scene Parsing](https://arxiv.org/pdf/2502.06219)

**Sicen Guo**, Tianyou Wen, Chuangwei Liu, Qijun Chen, Rui Fan
</div>
</div>
</div>

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->


<span class="anchor" id="-projects"></span>

# 💻 Internships
- *2025.10 - Present*, Data Engineer Intern @ [Tesla](https://www.linkedin.com/company/tesla-motors/posts/?feedView=all)
- *2025.06 - 2025.10*, Account Tech Strategist Intern @ [Microsoft](https://www.linkedin.com/company/microsoft/posts/?feedView=all)
- *2024.12 - 2025.02*, Application Engineer Intern @ Metaverse



# 🎓 Selected Projects
- *2025.6-2025.9*: 

  **Customer Profiling Agent (ATU Agent)**

  A multi agent research system that conducts deep local and web research and generates a long report with citations.

  [[GitHub]](https://github.com/embracefailure/ATU-Agent)
- *2025.3*: &nbsp;Worked on [Lerobot](https://github.com/embracefailure/lerobot), trained a policy using [ALOHA ACT](https://github.com/tonyzhaozh/aloha) on the [mobile_shrimp](https://huggingface.co/datasets/lerobot/aloha_mobile_shrimp) dataset.
- *2025.3*: &nbsp;Contributed to this [Embodied AI Guide](https://github.com/TianxingChen/Embodied-AI-Guide). Happy to be a part of the community!
- *2025.2*: &nbsp;I worked on using Reinforcement Learning to recycle a virtual rocket. Based on this GitHub project [Rocket Recycling using RL](https://github.com/jiupinjia/rocket-recycling). I find this [Explanation on Actor-Critic Algorithm](https://www.geeksforgeeks.org/actor-critic-algorithm-in-reinforcement-learning/) really helpful.  
- *2025.1*: &nbsp;Used Knowledge Distillation to transfer knowledge from a DNN for image classification task on CIFAR-10. With the help of [Pytorch Tutorials](https://pytorch.org/tutorials/beginner/knowledge_distillation_tutorial.html) 

<div class="projects-media-section">
  <!-- 项目演示图片 -->
  <div class="media-box">
    <img src="/images/projects/embodied_ai_guide.png" alt="Embodied AI Guide" style="width: 60%;">
    <div class="media-caption">My contributions to the Embodied AI Guide</div>
  </div>
  
  <!-- 项目演示视频 -->
  <div class="media-box">
    <video style="width: 60%;" controls>
      <source src="/videos/projects/aloha_act.mp4" type="video/mp4">
    </video>
    <div class="media-caption">Collecting data using ALOHA @ Shanghai Innovation Institute</div>
  </div>
</div>

<style>
.media-box {
  text-align: center;
  margin-bottom: 20px;
}
.media-caption {
  margin-top: 10px;
}
</style>

<!-- - *2025.3*: &nbsp;When learning SQL, I find this [SQL Tutorial](https://sqlzoo.net/wiki/SQL_Tutorial) helpful.  -->
<!-- - *2025.3*: &nbsp;Compared Grok3 with GPT o3 mini on coding problem. Turned out that Grok outperforms GPT on generating code for this [ball throwing game](https://github.com/embracefailure/game-animation). -->

<span class="anchor" id="-educations"></span>

# 📖 Educations
- *2022 - 2026*, Tongji University – School of Electronic and Information Technology
  - Bachelor's Degree in Electrical Engineering. 
- *2024 - 2025*, Self-Directed Study  
  - Completed [**CS231n: Convolutional Neural Networks for Visual Recognition**](https://cs231n.stanford.edu/) (Stanford University)  
  - Completed [**CS287: Advanced Robotics**](https://people.eecs.berkeley.edu/~pabbeel/cs287-fa19/) (UC Berkeley, taught by Pieter Abbeel)
<!-- - *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

<span class="anchor" id="-honors-and-awards"></span>

# 🎖 Honors and Awards
- *2024.12* 🥇First-Class Scholarship for Outstanding Students, Tongji University (Top 5%)
- *2023.12* 🥉Third-Class Scholarship for Outstanding Students, Tongji University (Top 15%)
<!-- - *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->



<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->



<!-- <span class="anchor" id="-mentor"></span>

# 🪂 Mentor
I greatly admire **Elon Musk**, an entrepreneur who uses technology and first principles to drive humanity forward. His visionary approach inspires me to innovate and create meaningful solutions. -->

<!-- <span class="anchor" id="-non-tech"></span>

# 🏞️ Non-Tech Traits 
- **Effective Communication**: I excel at authentic networking and connecting with others, allowing me to build meaningful relationships.
- **Storytelling**: I have the ability to simplify complex technological concepts, making them accessible to my peers and community.
  
As a **Microsoft Student Ambassador**, I not only develop applications but also build and maintain the Microsoft Student Ambassador community. I have organized **7 tech-sharing events** to empower others with Microsoft technologies. My contributions include creating video content related to the Microsoft Student Ambassador community on **Bilibili**, which has garnered nearly **2,500 views** across **six videos**. My live stream sharing event cooperating with Microsoft MVPs reached **2000 audiences**.  -->

<span class="anchor" id="-life"></span>

# 🚀 Life
- I want to **constantly learn** about the latest cutting-edge technologies and engage in discussions with innovative thinkers.

- I also desire to have leisure time to **travel** the world, **connecting** and making friends with people from diverse backgrounds. 

- I want to try all sorts of **sports** and maintain an interest in some of them. Enjoy playing golf (Varsity Team), swimming (Varsity Team), baseball(Varsity Team), american football, basketball, tennis, soccer, running, and badminton so far. 

- Ultimately, I want to be someone that others enjoy being around.
