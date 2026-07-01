---
title: "InftyThink+: Effective and Efficient Infinite-Horizon Reasoning via Reinforcement Learning"
collection: publications
category: conferences
permalink: /publication/2026-07-01-inftythink-plus
excerpt: '<b>Yuchen Yan</b>, Liang Jiang, Jin Jiang, Shuaicheng Li, zujie wen, Zhiqiang Zhang, JUN ZHOU, Jian Shao, Yueting Zhuang, Yongliang Shen (&dagger; first author)'
date: 2026-07-01
venue: 'ICML 2026'
paperurl: 'https://openreview.net/forum?id=tyul8kXaJU'
tldr: 'Scales infinite-horizon reasoning with reinforcement learning for more effective and efficient long thinking.'
authorship: first
keywords:
  - "LLM Reasoning"
  - "Efficient Reasoning"
  - "Reinforcement Learning"
---

## Abstract

Large reasoning models achieve strong performance by scaling inference-time chain-of-thought, but this paradigm suffers from quadratic cost, context length limits, and degraded reasoning due to lost-in-the-middle effects. Iterative reasoning mitigates these issues by periodically summarizing intermediate thoughts, yet existing methods rely on supervised learning or fixed heuristics and fail to optimize when to summarize, what to preserve, and how to resume reasoning. We propose InftyThink+, an end-to-end reinforcement learning framework that optimizes the entire iterative reasoning trajectory, building on model-controlled iteration boundaries and explicit summarization. InftyThink+ adopts a two-stage training scheme with supervised cold-start followed by trajectory-level reinforcement learning, enabling the model to learn strategic summarization and continuation decisions. Experiments on DeepSeek-R1-Distill-Qwen-1.5B show that InftyThink+ improves accuracy by 21% on AIME24 and outperforms conventional long chain-of-thought reinforcement learning by a clear margin, while also generalizing better to out-of-distribution benchmarks. Moreover, InftyThink+ significantly reduces inference latency and accelerates reinforcement learning training, demonstrating improved reasoning efficiency alongside stronger performance.
