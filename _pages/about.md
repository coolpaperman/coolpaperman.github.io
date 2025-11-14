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

I am a Ph.D. student at the School of Computer Science and Technology, Tongji University, supervised by Prof. Liang Hu (**Head of the Collaborative and Intelligent Computing Laboratory**). My main research interests include **Continual Learning, Machine Unlearning, Brain-inspired AI, and Model Memory Mechanisms**, with a focus on exploring and developing innovative methods to enable machine learning models to learn, forget, and manage their own memory in a manner similar to the human brain.

I hold a Master’s degree in Science, majoring in Mathematics, under the supervision of **Prof. Feilong Cao** at Chian Jiliang University (also thanks to **Prof. Hailing Ye** at Chian Jiliang University and **Prof. Ming Li** at Zhejiang Normal University). My academic background combines strong theoretical foundations with practical skills, enabling interdisciplinary research.

I am open to collaborations with researchers and teams sharing interests in **Lifelong Learning**, aiming to explore novel research directions, exchange ideas, and advance the application of related technologies in practice.


# 🔥 News

- *2025.10*: &nbsp;🎉🎉 Visited the research group of Prof. Xipeng Qiu at Shanghai Innovation Institute.
- *2025.08*: &nbsp;🎉🎉 One paper is accepted by *IEEE Transactions on Pattern Analysis and Machine Intelligence* (JCR-Q1, 中科院1区Top, CCF-A, IF=18.6).
- *2025.05*: &nbsp;🎉🎉 Built a good academic collaboration with Prof. Usman Naseem’s team at Macquarie University.
- *2024.12*: &nbsp;🎉🎉 Awarded the Excellent Master’s Thesis of Zhejiang Province.
- *2024.10*: &nbsp;🎉🎉 Built a good academic collaboration with Prof. Hongying Zhao’s team at Tongji University.
- *2024.07*: &nbsp;🎉🎉 Built a good academic collaboration with Prof. Longbin Cao’s team at Macquarie University.
- *2023.10*: &nbsp;🎉🎉 One paper is accepted by *Pattern Recognition* (JCR-Q1, 中科院1区Top, CCF-B). 
- *2023.01*: &nbsp;🎉🎉 One paper is accepted by *Neural Networks* (JCR-Q1, 中科院2区Top, CCF-B). 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI 2025</div><img src='images/TPAMI-2025.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Graph Memory Learning: Imitating Lifelong Remembering and Forgetting of Brain Networks](https://ieeexplore.ieee.org/abstract/document/11129878)

**Jiaxing Miao**, Liang Hu, Qi Zhang, Longbin Cao

This paper introduces a new concept of graph memory learning. Its core idea is to enable a graph model to selectively remember new knowledge but forget old knowledge. Building on this idea, the paper presents a novel graph memory learning framework *Brain-inspired Graph Memory Learning (BGML)*, inspired by brain network dynamics and function-structure coupling strategies.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2025</div><img src='images/Arxiv-25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Reliable Curriculum Unlearning via the Right Forgotten Pathway](https://arxiv.org/abs/2509.14633)

**Jiaxing Miao**, Liang Hu, Qi Zhang, Zhongyuan Lai, Tangwei Ye and Usman Naseem

This paper proposes *CUFG (Curriculum Unlearning via Forgetting Gradients)*, a novel framework that enhances the stability of approximate unlearning through innovations in both forgetting mechanisms and data scheduling strategies. Specifically, CUFG integrates a new gradient corrector guided by forgetting gradients for fine-tuning-based unlearning and a curriculum unlearning paradigm that progressively forgets from easy to hard.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">PR 2023</div><img src='images/PR-2023.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Triplet teaching graph contrastive networks with self-evolving adaptive augmentation](https://www.sciencedirect.com/science/article/pii/S0031320323003850)

**Jiaxing Miao**, Feilong Cao, Ming Li, Bing Yang, Hailiang Ye

Building on the teaching concept, this paper proposes a novel *triplet-based teaching graph contrastive network with self-evolving adaptive augmentation (T-GCSA)*. It addresses the critical challenges of generating reasonable augmented views, utilizing them effectively, and constructing efficient, comprehensive contrastive objectives.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NN 2023</div><img src='images/NN-2023.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Revisiting graph neural networks from hybrid regularized graph signal reconstruction](https://www.sciencedirect.com/science/article/pii/S0893608022004439)

**Jiaxing Miao**, Feilong Cao, Hailiang Ye, Ming Li, Bing Yang,

This paper presents a unified optimization framework from hybrid regularized graph signal reconstruction to establish the connection between the aggregation operations of different GNNs. We use this new framework to mathematically explain several classic GNN models and summarizes their commonalities and differences from a macro perspective. Based on this, we design the new model, *GNN based on model-driven and data-driven (GNN-MD)*. We also theoretically analyze its convergence.
</div>
</div>

# 🎖 Honors and Awards
- *2024.12*: My master's thesis titled 'Interpretable Graph Representation LearningUnder Semi-Supervised and Unsupervised' was awarded the Excellent Master’s Thesis of Zhejiang Province.
- *2021.12*: Won the second prize in the 18th 'Huawei Cup' National Graduate Mathematical Modeling Competition in China.


# 📖 Educations
- *2023.09 - now*, Ph.D. student, the Department of Computer Science and Technology, Tongji University, Shanghai 201804, China. 
- *2020.09 - 2023.06*, Master. the Department of Mathematics, China Jiliang University, Hangzhou 310018, China.
- *2016.09 - 2020.06*, Undergraduate. the Department of Mathematics, Zhejiang Ocean University, Zhoushan 310018, China.

# 💻 Academic Service
- Serving as PC Member and reviewer for ACM Web Conference 2026.
- Serving as a reviewer for The 39-th Annual Conference on Neural Information Processing Systems (2025).
- Serving as a reviewer for IEEE Transactions on Neural Networks and Learning Systems.
