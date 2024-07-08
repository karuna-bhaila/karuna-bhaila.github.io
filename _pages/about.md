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

I am a CS Ph.D. student in the [SAIL](https://sail.uark.edu/) lab advised by [Dr. Xintao Wu](http://www.csce.uark.edu/~xintaowu/) at the University of Arkansas.

My research focuses on graph machine learning with an emphasis on trustworthy learning, especially privacy and fairness. 
I am also broadly interested in trustworthy foundation models, graph foundation models and applications of LLMs on graph data.
Currently, I am also working on applications of graph machine learning in physical systems such as critical infrastructure networks.

<!--# 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
-->

# 📝 Preprints

- Soft Prompting for Unlearning in Large Language Models [[Paper]](https://arxiv.org/pdf/2406.12038) [[Code]](https://github.com/karuna-bhaila/llm_unlearning) \
Karuna Bhaila, Minh-Hao Van, Xintao Wu \
ArXiV 2024

- DP-TabICL: In-Context Learning with Differentially Private Tabular Data [[Paper]](https://arxiv.org/pdf/2403.05681) \
Alycia N. Carey\*, Karuna Bhaila\*, Kennedy Edemacu, Xintao Wu \
ArXiV 2024

# 📝 Publications

- Local Differential Privacy in Graph Neural Networks: a Reconstruction Approach [[Paper]](https://epubs.siam.org/doi/10.1137/1.9781611978032.1) [[Code]](https://github.com/karuna-bhaila/RGNN) \
Karuna Bhaila, Wen Huang, Yongkai Wu, Xintao Wu \
Proceedings of the 2024 SIAM International Conference on Data Mining (SDM) \
*Also at NeurIPS 2023 Workshop New Frontiers in Graph Learning (GLFrontiers)

- Cascading Failure Prediction in Power Grid Using Node and Edge Attributed Graph Neural Networks [[Paper]](https://ai-2-ase.github.io/papers/25%5CCameraReady%5Ccamera_ready_cascade_gnn.pdf) [[Code]](https://github.com/karuna-bhaila/gnn-cascading-failure) \
Karuna Bhaila, Xintao Wu \
Proceedings of the 2024 International Joint Conference on Neural Networks (IJCNN) \
*Also at AAAI 2024 Workshop on AI to Accelerate Science and Engineering (AI2ASE)

- Randomized Response Has No Disparate Impact on Model Accuracy [[Paper]](https://ieeexplore.ieee.org/abstract/document/10386574) [[Code]](https://github.com/alycia-noel/ldp-disparate-impact) \
Alycia N. Carey, Karuna Bhaila, Xintao Wu \
Proceedings of 2023 IEEE International Conference on Big Data 

- Fair Collective Classification in Networked Data [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10020610) \
Karuna Bhaila, Yongkai Wu, Xintao Wu \
Proceedings of 2022 IEEE International Conference on Big Data \
*Also at KDD 2022 Workshop on Ethical Artificial Intelligence: Methods and Applications (EAI-KDD) 

# 🎖 Honors and Awards
- *2024.04*: SIAM Student Travel Award
- Reginald R. 'Barney' & Jameson A. Baxter Graduate Fellowship
- College of Engineering Graduate Fellowship
- Webster International Scholarship

# 💻 Experience
- *2020.09 - 2021.07*: Developer, ITSutra
- *2019.08 - 2020.05*: Data Analyst, FDC Webster University
- *2019.05 - 2019.07*: Intern, Jenzabar

# 💬 Teaching
- Lecturer, Python and Machine Learning @ Multidisciplinary Bootcamp (MDaS), University of Arkansas 
- Guest Lecturer, CSCE 4143 Data Mining, University of Arkansas
- Math and CS Tutor, Webster University

# Services
Conference Reviewer
- International Joint Conference on Neural Networks (IJCNN)

Journal Reviewer
- Transactions on Big Data (TBD)
- Human-Centric Intelligent Systems (HCIN)

Workshop Reviewer
- KDD Workshop on Ethical Artificial Intelligence: Methods and Applications (EAI-KDD)
