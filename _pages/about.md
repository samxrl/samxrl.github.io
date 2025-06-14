---
permalink: /
title: ""
#excerpt: ""
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

I am a Ph.D. student at Southeast University, supervised by Professor [Bixin Li](https://scholar.google.com/citations?hl=zh-CN&user=nxQBSlgAAAAJ). I received my Master's degree from Beijing Information Science and Technology University, under the supervision of Professor [Zhanqi Cui](https://zqcui.github.io/).

My research interests include SE4AI, trustworthy AI, and LLM safety. If you are interested in my research, please feel free to contact me. 🙌


# 🔥 News
- *2024.11*: &nbsp;🎉🎉 One paper is accepted by TOSEM. 


# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badgeImg">TOSEM (CCF-A)</div><img src='../images/IATT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[IATT: Interpretation Analysis-based Transferable Test Generation for Convolutional Neural Networks](https://dl.acm.org/doi/10.1145/3705301)

**Ruilin Xie**, Xiang Chen, Qifan He, Bixin Li, Zhanqi Cui
- Proposes a new test scenario for black-box CNN models. In this scenario, the testing method
 generates transferable test inputs for the BTM by analyzing a WSM with similar functionalities
 to the target black-box model.
- Proposes an IATT method for the new testing scenario. By iteratively optimizing the trans
ferability and realism of the test inputs, the test inputs generated by IATT can be effectively
 test models with different model structures, training sets, or task domains.

🖥️[**Code**](https://github.com/samxrl/IATT)
</div>
</div>


- <span class="badge">软件学报</span> &nbsp; **IADT: 基于解释分析的深度神经网络差分测试**

    <span style="font-size:15px;"> <strong><em>谢瑞麟</em></strong>, 崔展齐, 陈翔, 李莉.</span>
    <span style="font-size:15px;">软件学报, 2024. (<span style="color:blue">中文CCF-A</span>)</span>

    📃[**Paper**](https://www.jos.org.cn/jos/article/abstract/7088)

- <span class="badge">软件学报</span> &nbsp; **IATG: 基于解释分析的自动驾驶软件测试方法**

    <span style="font-size:15px;"> <strong><em>谢瑞麟</em></strong>, 崔展齐, 陈翔, 郑丽伟.</span>
    <span style="font-size:15px;">软件学报, 2024. (<span style="color:blue">中文CCF-A</span>)</span>

    📃[**Paper**](https://www.jos.org.cn/jos/article/abstract/6836)

- <span class="badge">软件学报</span> &nbsp; **DeepRanger:覆盖制导的深度森林测试方法**

    <span style="font-size:15px;"> 崔展齐, <strong><em>谢瑞麟</em></strong>, 陈翔, 刘秀磊, 郑丽伟.</span>
    <span style="font-size:15px;">软件学报, 2023. (<span style="color:blue">中文CCF-A, 导师一作</span>)</span>

    📃[**Paper**](https://www.jos.org.cn/jos/article/abstract/6422)

- <span class="badge">计算机研究与发展</span> &nbsp; **基于可解释性分析的深度神经网络优化方法**

    <span style="font-size:15px;"> 吴欢欢, <strong><em>谢瑞麟</em></strong>, 乔塬心, 陈翔, 崔展齐.</span>
    <span style="font-size:15px;">计算机研究与发展, 2024. (<span style="color:blue">中文CCF-A</span>)</span>

    📃[**Paper**](https://crad.ict.ac.cn/article/doi/10.7544/issn1000-1239.202220803)

- <span class="badge">DSA</span> &nbsp; **Testing Coverage Criteria for Deep Forests**

    <span style="font-size:15px;"> <strong><em>Ruilin Xie</em></strong>, Zhanqi Cui, Minghua Jia, Yuan Wen and Baoshui Hao.</span>
    <span style="font-size:15px;">2019 6th International Conference on Dependable Systems and Their Applications (DSA), 2020. (<span style="color:blue">EI</span>)</span>

    📃[**Paper**](https://ieeexplore.ieee.org/document/9045858)


- <span class="badge">SMC</span> &nbsp; **Perturbing and Backtracking based Textual Adversarial Attack**

    <span style="font-size:15px;"> Yuanxin Qiao, <strong><em>Ruilin Xie</em></strong>, Songcheng Xie and Zhanqi Cui.</span>
    <span style="font-size:15px;">2024 IEEE International Conference on Systems, Man, and Cybernetics (SMC), 2024. (<span style="color:blue">CCF-C</span>)</span>

    📃[**Paper**](https://ieeexplore.ieee.org/document/10366669)


- <span class="badge">QRS</span> &nbsp; **DeepIA: An Interpretability Analysis based Test Data Generation Method for DNN**

    <span style="font-size:15px;"> Qifan He, <strong><em>Ruilin Xie</em></strong>, Li Li, Zhanqi Cui.</span>
    <span style="font-size:15px;">the IEEE 23rd IEEE International Conference on Software Quality, Reliability, and Security (QRS), 2023. (<span style="color:blue">CCF-C</span>)</span>

    📃[**Paper**](https://ieeexplore.ieee.org/document/10366669)

- <span class="badge">SMC</span> &nbsp; **MOBTAG: Multi-objective Optimization based Textual Adversarial Example Generation**

    <span style="font-size:15px;"> Yuanxin Qiao, <strong><em>Ruilin Xie</em></strong>, Li Li, Qifan He, Zhanqi Cui.</span>
    <span style="font-size:15px;">the IEEE International Conference on Systems, Man, and Cybernetics (SMC), 2023. (<span style="color:blue">CCF-C</span>)</span>

    📃[**Paper**](https://ieeexplore.ieee.org/document/10394175)

- <span class="badge">SANER Workshop</span> &nbsp; **SICUP: A Comment Updating Approach based on Structural Information**

    <span style="font-size:15px;"> Shifan Liu, Zhanqi Cui*, <strong><em>Ruilin Xie</em></strong>.</span>
    <span style="font-size:15px;">1st International Workshop on Software Engineering & Deep Learning(SE&DL), co-located with SANER 2023. (<span style="color:blue">EI</span>)</span>

    📃[**Paper**](https://ieeexplore.ieee.org/document/10123654)



# 🎖 Honors and Awards
- *2024* Beijing’s Outstanding Master’s Degree Graduates
- *2024* Outstanding Graduation Thesis. 
- *2023* Graduate National Scholarship. 
- *2023* Graduate Academic Scholarship Third Prize.
- *2023* High‑Level Academic Paper Award Second Prize.
- *2022* Graduate Academic Scholarship First Prize.
- *2022* Graduate Outstanding Research Achievement Award.

# 📖 Educations
- *2024.06 - (now)*, PhD in Software Engineering, Southeast University. 
- *2021.09 - 2024.06*, Master in Computer Technology, Beijing Information Science and Technology University. 
- *2015.06 - 2019.09*, Undergraduate in Software Engineering. Beijing Information Science and Technology University. 

[//]: # (# 💬 Invited Talks)

[//]: # (- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. )

[//]: # (- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]]&#40;https://github.com/&#41;)

[//]: # (# 💻 Internships)

[//]: # (- *2019.05 - 2025.02*, [Lorem]&#40;https://github.com/&#41;, China.)