---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **Ph.D. in Artificial Intelligence**, Zhejiang University, 2022 – present
  * Member of [REAL Lab](https://zju-real.github.io), advised by Dr. Yongliang Shen and Dr. Jian Shao
  * Research directions: LLM reasoning, AI agents
  * Coursework: Natural Language Processing, Knowledge Graphs, Knowledge Reasoning & Representation
* **B.S. in Information Management and Information Systems**, Beijing Normal University, 2018 – 2022
  * Minor: **Data Science and Big Data Technology**, Beijing Normal University, 2020 – 2022

Honors & Awards
======
* National Scholarship (国家奖学金)
* Beijing Merit Student (北京市三好学生)
* Beijing Outstanding Graduate (北京市优秀毕业生)

Internships
======
* **Tencent, Hunyuan Foundation Model Team** (Qingyun Program), Apr 2026 to present
  * Vision post-training: SFT, OPD, and RL optimization
  * Subjective-task RL for Yuanbao user scenarios; SFT-RL post-training strategies
  * Multi-teacher distillation (OPD) for large-scale MoE models
* **Ant Group, Ling Foundation Model Team**, Aug 2025 to Apr 2026
  * Capability optimization of the Ring series of reasoning LLMs; adaptive reasoning-effort tuning
  * Co-authored the Ring-1T technical report (trillion-parameter reasoning model)
  * Agent-based SWE task capabilities; RL research for LLMs
* **Meituan, LongCat Foundation Model Team**, Jun 2023 to Jul 2025
  * Math-specialized data cleaning, preprocessing, and mixing across pre-training, annealing, and alignment stages
  * Training experience with Dense and MoE models (1B / 7B / >100B parameters)
  * Built data-synthesis and evaluation pipelines and code frameworks

Skills
======
* **Programming**: Python (advanced features), Git, Linux
* **LLM training & inference**: Megatron-Core (pre-training / fine-tuning), veRL (RL framework), vLLM, SGLang

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
