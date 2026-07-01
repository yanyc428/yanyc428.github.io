---
title: "Let LRMs Break Free from Overthinking via Self-Braking Tuning"
collection: publications
category: conferences
permalink: /publication/2025-12-02-self-braking-tuning
excerpt: 'Haoran Zhao*, <b>Yuchen Yan</b>*, Yongliang Shen, Haolei Xu, Wenqi Zhang, Kaitao Song, Jian Shao, Weiming Lu, Jun Xiao, Yueting Zhuang (* co-first author)'
date: 2025-12-02
venue: 'NeurIPS 2025'
paperurl: 'https://openreview.net/forum?id=u3a2AX0icx'
tldr: 'Teaches reasoning models to stop overthinking by learning when to brake.'
authorship: cofirst
keywords:
  - "Large Reasoning Models"
  - "Efficient Reasoning"
---

## Abstract

Large reasoning models (LRMs), such as OpenAI o1 and DeepSeek-R1, have significantly enhanced their reasoning capabilities by generating longer chains of thought, demonstrating outstanding performance across a variety of tasks. However, this performance gain comes at the cost of a substantial increase in redundant reasoning during the generation process, leading to high computational overhead and exacerbating the issue of overthinking. Although numerous existing approaches aim to address the problem of overthinking, they often rely on external interventions. In this paper, we propose a novel framework, **Self-Braking Tuning**(SBT), which tackles overthinking from the perspective of allowing the model to regulate its own reasoning process, thus eliminating the reliance on external control mechanisms. We construct a set of overthinking identification metrics based on standard answers and design a systematic method to detect redundant reasoning. This method accurately identifies unnecessary steps within the reasoning trajectory and generates training signals for learning self-regulation behaviors. Building on this foundation, we develop a complete strategy for constructing data with adaptive reasoning lengths and introduce an innovative braking prompt mechanism that enables the model to naturally learn when to terminate reasoning at an appropriate point. Experiments across mathematical benchmarks (AIME, AMC, MATH500, GSM8K) demonstrate that our method reduces token consumption by up to 60\% while maintaining comparable accuracy to unconstrained models.
