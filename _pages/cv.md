---
layout: archive
title: "CV"
title_zh: "简历"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<div class="lang-en" markdown="1">

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

</div>

<div class="lang-zh" markdown="1">

教育背景
======
* **浙江大学 · 人工智能 · 博士研究生**，2022.09 – 至今
  * [REAL Lab](https://zju-real.github.io) 成员，导师为沈永亮老师和邵健老师
  * 课程：自然语言处理、知识图谱、知识推理与表示
* **北京师范大学 · 信息管理与信息系统 · 学士**，2018.09 – 2022.06
  * 辅修：**数据科学与大数据技术**，北京师范大学，2020 – 2022

研究方向
======
* **大模型后训练**：聚焦大语言/多模态模型的 SFT 与 RL 训练范式，提升模型的推理、Agentic 与主观对齐能力
* **奖励建模与强化学习**：面向可靠、可扩展的奖励信号设计与验证机制，支撑大规模强化学习训练
* **AI 智能体**：面向真实场景的智能体能力建设，提升复杂任务下的自主决策与执行效果

荣誉奖项
======
* 国家奖学金
* 北京市三好学生
* 北京市优秀毕业生

实习经历
======
* **腾讯集团 · 混元基座大模型团队**（基座组实习 · 青云计划），2026.04 – 至今
  * *VLM 视觉后训练*
    * 参与 VLM 后训练中 SFT 合版，沉淀与各专项的合版协作方式方法，训练模型为后续 RL 提供起点
    * 面向主观类能力的 Pairwise RL，提升 RL 训练效率约 4 倍，取得 10% 显著的主观任务能力提升，合入生产 Recipe
    * 面向主观类能力的 Rubric RL，探索 Rubric 生产机制与 Judgement 优化方式，进一步提升主观类任务能力
    * VisualAgent 能力建设，从 Harness、模型强化学习训练、自蒸馏等角度，探索视觉智能体在多模态任务中的能力提升
    * Toolbox 建设，支撑组内基于 VisualAgent 的数据合成、数据质检、离线评测、Harness 迭代、Tools 迭代等
* **蚂蚁集团 · Ling 基座大模型团队**（基座组研究型实习），2025.08 – 2026.04
  * *Ring 推理大模型*
    * 建设模型 Reasoning Effort 能力，通过 SFT-RL 协同优化，使模型支持 Low、Medium、High、xHigh 等不同推理深度
    * 优化模型面向 SWE 任务的 Agentic 能力，通过 SFT-RL 两阶段优化，在 SWE-Bench 提升约 6%
    * 探索智能体 Context Compaction 能力，模型在 Long-CoT 模式下，推理时延降低 40%，推理效果提升 9%
    * 参与 Ring-1T 技术报告撰写，了解万亿参数推理大模型的完整训练流程与技术难点
* **美团集团 · LongCat 基座大模型团队**（基座组实习），2023.06 – 2025.07
  * *数学推理专项*
    * 负责数学推理专项在预训练 / 退火 / SFT 的合版，向主线交付各阶段数学数据，提升主线模型数学推理能力
    * 合成数学推理的指令数据用于退火阶段训练，开展多样性的 Query 合成和可控的 Response 合成，综合性能提升 11%
    * 具备 Dense 与 MoE 架构下 1B / 7B / 100B+ 等不同参数量模型的预训练 / 微调 / 强化训练经验
    * 构建面向团队的数据合成与评测代码框架，便于 benchmark 快速接入与想法快速验证，提升团队整体开发效率
  * *通用 SFT 合版*
    * 参与模型主线指令微调数据生产、数据清洗与数据版本管理，并设计和实验专项能力融合方案
    * 参与长文本专项相关工作，整合并支持长文本评测，探索位置编码插值方案，主线模型上下文窗口接近无损地扩大 8 倍
    * 参与工具调用专项相关工作，完成 0-1 的工具调用能力支持，同时维持模型通用能力

个人技能
======
* **大模型训练**：熟练基于 Megatron-Core 等框架的大模型预训练与微调全流程，具备 Dense 与 MoE 架构下 1B ~ 100B+ 不同参数量模型的训练调优经验，覆盖并行策略选择、训练稳定性与吞吐效率优化
* **强化学习**：熟练使用 veRL 强化学习框架，具备从 Rollout、奖励计算到策略更新的大规模 RL 训练链路搭建与调优经验；熟练使用 vLLM、SGLang 等推理引擎进行高效 Rollout 加速与模型部署
* **工程基础**：熟练使用 Python 及其高级特性（多进程/多线程、异步编程、装饰器等）；熟练使用 Git 进行多人协作开发；掌握 Linux 常用命令与 Shell 脚本，具备在集群上提交多机多卡训练任务与调试分布式程序的经验
* **框架研发**：独立设计与研发大模型评测框架（Benchmark 快速接入、分布式并行推理、结果自动统计）与数据合成框架（Query 多样性合成、Response 可控生成、质量过滤）

</div>
