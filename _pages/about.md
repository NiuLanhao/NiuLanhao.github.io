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

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. Suspendisse condimentum, libero vel tempus mattis, risus risus vulputate libero, elementum fermentum mi neque vel nisl. Maecenas facilisis maximus dignissim. Curabitur mattis vulputate dui, tincidunt varius libero luctus eu. Mauris mauris nulla, scelerisque eget massa id, tincidunt congue felis. Sed convallis tempor ipsum rhoncus viverra. Pellentesque nulla orci, accumsan volutpat fringilla vitae, maximus sit amet tortor. Aliquam ultricies odio ut volutpat scelerisque. Donec nisl nisl, porttitor vitae pharetra quis, fringilla sed mi. Fusce pretium dolor ut aliquam consequat. Cras volutpat, tellus accumsan mattis molestie, nisl lacus tempus massa, nec malesuada tortor leo vel quam. Aliquam vel ex consectetur, vehicula leo nec, efficitur eros. Donec convallis non urna quis feugiat.

My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).


# 🔥 Projects

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">03/2024 - 07/2024</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Integrated Platform for Classic Text Translation and Learning Based on Large Language Models](https://github.com/NiuLanhao/classic_text_translation)

- The ChatGLM model was fine-tuned with *P-Tuning v2* to improve classical text translation. It includes a multilingual corpus from the “Twenty-Four Histories,” supporting translations among classical Chinese, English, and modern Chinese.
- A *RAG* system was developed using the *LlamaIndex framework* and a custom “Xunzi” model. Additionally, a *WeChat mini-program* was created for mobile translation of classical texts.

</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">01/2023 - 06/2024</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Rice Yield Prediction Based on UAV Imagery](https://github.com/NiuLanhao/rice_segmentation)

- Elevated detection precision by transitioning from the *YOLOv5* single-stage approach (accuracy 0.457) to the two-stage *Cascade R-CNN*, achieving an enhanced accuracy of *0.844*.
- Enhanced rice instance segmentation accuracy by shifting from *Mask R-CNN* (accuracy 0.601) to *Cascade R-CNN with integrated masks*, resulting in an improved accuracy of *0.71*.

</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">03/2024 - 05/2024</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Zhipu Legal Charter: RAG-based Integrated Civil Law Platform](https://github.com/NiuLanhao/legal_rag)

- The project implemented *Retrieval-Augmented Generation (RAG)* with the *Zilliz vector database* for case retrieval in civil litigation. An *inverted index* was used to enhance search functionality for users unfamiliar with legal terminology.
- A civil law awareness platform was developed using *Django* and *Vue*, featuring a web interface and administrative CRUD functionalities for a MySQL database.

</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">02/2024 - 05/2024</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Momentum Analysis: The Movement of Tennis ](https://github.com/NiuLanhao/tennis_momentum_analysis)

- Data preprocessing utilized a *BP neural network* to extract eight features for player performance evaluation. An evaluation system linked player momentum to final victory using the *Kruskal-Wallis H test*.
- *MNN and RBP models* identified key indicators of match momentum, incorporating past data for improved suggestions. Performance metrics (Precision, Recall, F1 score, Accuracy) showed reliable score prediction.

</div></div>


# 🎖 Honors and Awards
- *2024.07* [2024 (The 17th) Chinese Collegiate Computing Competition](https://jsjds.blcu.edu.cn/info/1042/1963.htm), First Prize (Top 4%).
- *2024.05* [2024 (The 17th) Chinese Collegiate Computing Competition(Jiangsu Province)](https://www.jscs.org.cn/x4.php?id=99), Special Prize (Top 10%).
- *2024.05* [2024 (The 17th) Chinese Collegiate Computing Competition(Jiangsu Province)](https://www.jscs.org.cn/x4.php?id=99), Third Prize.
- *2022.09* Second Class Scholarship.

# 📖 Educations
- *2021.09 - 2025.06 (now)*, Undergraduate, Nanjing Agricultural University, Nanjing(China). 

# 💻 Internships
- *2024.05 - present (now)*, [Zhipu AI](https://www.zhipuai.cn/), Beijing(China).


