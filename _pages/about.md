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

I am a Postdoc at Harvard Medical School working with <a href="https://yulab.hms.harvard.edu/">Dr. Kun-Hsing Yu</a>. I obtained my Ph.D. in Biomedical Engineering (BME) from the University of Science and Technology of China (USTC) in June 2024. Before that, I got my B.E. degree from USTC in 2019.

My primary research interests lie in computational pathology, focusing on the quantitative analysis of pathology images. I am dedicated to developing advanced models with the long-term goal of reducing pathologists' workload and improving patients' survival. I have published 5+ papers with <a href='https://scholar.google.com/citations?user=fSOIIQMAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.


My research interest includes:
- Computational Pathology
- Pathology Image Analysis
- Medical Image Analysis

# 🔥 News
- *2023.12*: 🎉 A first-author paper is accepted by AAAI 2024!


# 🎓 Experiences
- <a href="https://hms.harvard.edu/"><img class="jpg" src="/images/hms_logo.jpg" width="46pt"></a> **2024.10 - Present**, 
Postdoctoral Research Fellow, Harvard Medical School. 
- <a href="http://en.ustc.edu.cn/"><img class="jpg" src="/images/ustcblue.jpg" width="46pt"></a> **2019.09 - 2024.06**, Ph.D., University of Science and Technology of China. 
- <a href="https://ucr.edu"><img class="jpg" src="/images/ucr.jpg" width="46pt"></a> **2018.07 - 2018.09**, Summer Research Intern, University of California, Riverside.
- <a href="https://en.ustc.edu.cn/"><img class="jpg" src="/images/ustcblue.jpg" width="46pt"></a> **2015.09 - 2019.06**, B.E., University of Science and Technology of China. 


# 📝 Publications 


### Journal

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Breast 2022</div><img src='images/breast2022.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- **Bao Li**, et al. Deep Learning with Biopsy Whole Slide Images for Pretreatment Prediction of Pathological Complete Response to Neoadjuvant Chemotherapy in Breast Cancer: A Multicenter Study. ***Breast***. 2022, 66: 183-190. (JCR:Q1; IF:5.7) 
[[HTML]](https://doi.org/10.1016/j.breast.2022.10.004) [[Code]](https://github.com/boyden/Pretreatment-Prediction-to-NAC-DLPM)
</div>
</div>


### Conference

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2024</div><img src='images/aaai2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- **Bao Li**, et al. Point Transformer with Federated Learning for Predicting Breast Cancer HER2 Status from Hematoxylin and Eosin-Stained Whole Slide Images. ***AAAI***. 2024, 38(4): 3000-3008. [[HTML]](https://arxiv.org/abs/2312.06454) [[Code]](https://github.com/boyden/PointTransformerFL)
</div>
</div>

- **Bao Li**, et al. Breast Cancer HER2 Status Prediction from Hematoxylin-Eosin Stained Images Using Point Cloud Transformer. ***In Proceedings of the 2023 San Antonio Breast Cancer Symposium***.

- **Bao Li**, et al. Multi-omics Fusion for Prediction of Response to Neoadjuvant Therapy in Breast Cancer with External Validation. ***In Proceedings of the 2021 San Antonio Breast Cancer Symposium***. [[News]](https://new.qq.com/rain/a/20211208A0AYHC00)


# 🏅 Honors and Awards
- *2022*  `First Class` Ph.D. Scholarship of the University of Science and Technology.
- *2021*  `Second Class` Ph.D. Scholarship of the University of Science and Technology.
- *2017.10* `Runner-up` in the 17th "RoboGame" of the University of Science and Technology (SV Team). [[News]](https://news.ustc.edu.cn/info/1056/62820.htm)

