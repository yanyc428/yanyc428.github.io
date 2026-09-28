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
* **Ph.D. in Artificial Intelligence**, Zhejiang University, Sep 2022 – present
  * Member of [REAL Lab](https://zju-real.github.io), advised by Dr. Yongliang Shen and Dr. Jian Shao
  * Coursework: Natural Language Processing, Knowledge Graphs, Knowledge Reasoning & Representation
* **B.S. in Information Management and Information Systems**, Beijing Normal University, Sep 2018 – Jun 2022
  * Minor: **Data Science and Big Data Technology**, Beijing Normal University, 2020 – 2022

Research Interests
======
* **LLM post-training**: SFT and RL recipes for language and multimodal models that improve reasoning, agentic, and subjective-alignment capabilities
* **Reward modeling & reinforcement learning**: reliable, scalable reward signals and verification mechanisms that support large-scale RL training
* **AI agents**: agents that make decisions and act reliably on complex, real-world tasks

Honors & Awards
======
* National Scholarship (国家奖学金)
* Beijing Merit Student (北京市三好学生)
* Beijing Outstanding Graduate (北京市优秀毕业生)

Internships
======
* **Tencent, Hunyuan Foundation Model Team** (Qingyun Program), Apr 2026 – present
  * *VLM visual post-training*
    * Contributed to merged SFT releases for VLM post-training and set up how capability tracks collaborate on them; the resulting model is the starting point for RL
    * Pairwise RL for subjective capabilities: about 4× faster RL training and a 10% gain on subjective tasks; merged into the production recipe
    * Rubric RL for subjective capabilities: explored how rubrics are produced and how judgments are optimized, further improving subjective tasks
    * Built VisualAgent capabilities for multimodal tasks through harness design, RL training, and self-distillation
    * Built the team toolbox for VisualAgent-based data synthesis, data quality checks, offline evaluation, and harness and tool iteration
* **Ant Group, Ling Foundation Model Team** (research intern), Aug 2025 – Apr 2026
  * *Ring reasoning models*
    * Built reasoning-effort control through joint SFT–RL optimization, supporting Low / Medium / High / xHigh reasoning depths
    * Improved agentic capability on software-engineering tasks with two-stage SFT–RL, gaining about 6% on SWE-Bench
    * Explored context compaction for agents: in long-CoT mode, 40% lower inference latency and 9% better results
    * Co-authored the Ring-1T technical report, covering the full training pipeline of a trillion-parameter reasoning model
* **Meituan, LongCat Foundation Model Team**, Jun 2023 – Jul 2025
  * *Math reasoning*
    * Owned math-reasoning data merges across pre-training, annealing, and SFT, delivering math data to the mainline model at each stage
    * Synthesized math instruction data for annealing, with diverse query synthesis and controllable response synthesis; 11% overall improvement
    * Pre-training, fine-tuning, and RL experience with Dense and MoE models at 1B / 7B / 100B+ scale
    * Built the team's data-synthesis and evaluation framework for fast benchmark onboarding and quick idea validation
  * *General SFT*
    * Produced, cleaned, and versioned mainline instruction-tuning data, and designed schemes for merging specialized capabilities
    * Long context: integrated long-context evaluation and explored positional-encoding interpolation, extending the mainline context window about 8× with little loss
    * Tool use: built tool-calling support from scratch while preserving general capabilities

Skills
======
* **LLM training**: end-to-end pre-training and fine-tuning with Megatron-Core; Dense and MoE models from 1B to 100B+, including parallelism strategy, training stability, and throughput optimization
* **Reinforcement learning**: large-scale RL pipelines with veRL, from rollout and reward computation to policy updates; fast rollout and deployment with vLLM and SGLang
* **Engineering**: Python (multiprocessing / multithreading, async, decorators), Git collaboration and branching, Linux and shell scripting, multi-node multi-GPU jobs on clusters and debugging distributed programs
* **Frameworks**: designed and built evaluation frameworks (fast benchmark onboarding, distributed inference, automatic result aggregation) and data-synthesis frameworks (diverse query synthesis, controllable response generation, quality filtering)
