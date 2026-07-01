---
title: "VerifyBench: Benchmarking Reference-based Reward Systems for Large Language Models"
collection: publications
category: conferences
permalink: /publication/2026-04-22-verifybench
excerpt: '<b>Yuchen Yan</b>, Jin Jiang, Zhenbang Ren, Yijun Li, Xudong Cai, Yang Liu, Xin Xu, Mengdi Zhang, Jian Shao, Yongliang Shen, Jun Xiao, Yueting Zhuang (&dagger; first author)'
date: 2026-04-22
venue: 'ICLR 2026'
paperurl: 'https://openreview.net/forum?id=JfsjGmuFxz'
tldr: 'A benchmark for evaluating reference-based reward systems that verify LLM answers.'
authorship: first
keywords:
  - "Reference-based reward bench"
  - "Reward for reinforcement learning"
---

## Abstract

Large reasoning models such as OpenAI o1 and DeepSeek-R1 have demonstrated remarkable performance in complex reasoning tasks. A critical component of their training is the incorporation of reference-based reward systems within reinforcement learning (RL), where model outputs are evaluated against ground truth references. However, existing reward benchmarks focus on preference comparisons between responses rather than evaluating verification against ground truth references, leaving a critical gap in our ability to evaluate verification systems used in reasoning model training. In this paper, we introduce VerifyBench and its challenging variant VerifyBench-Hard, two benchmarks specifically designed to assess reference-based reward systems. These benchmarks are constructed through meticulous data collection and curation, followed by careful human annotation to ensure high quality. Our comprehensive evaluation reveals that while larger model-based verifiers show promise on standard cases, all current systems demonstrate substantial room for improvement on challenging instances. Through systematic analysis of performance patterns across reasoning tasks and error categories, we provide insights for advancing reference-based reward systems. These benchmarks establish a standardized framework for improving verification accuracy, ultimately enhancing reasoning capabilities in models trained via RL.
