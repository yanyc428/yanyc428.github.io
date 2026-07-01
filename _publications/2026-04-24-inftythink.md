---
title: "InftyThink: Breaking the Length Limits of Long-Context Reasoning in Large Language Models"
collection: publications
category: conferences
permalink: /publication/2026-04-24-inftythink
excerpt: '<b>Yuchen Yan</b>, Yongliang Shen, Yang Liu, Jin Jiang, Mengdi Zhang, Jian Shao, Yueting Zhuang (&dagger; first author)'
date: 2026-04-24
venue: 'ICLR 2026'
paperurl: 'https://openreview.net/forum?id=T1h5em349L'
tldr: 'Breaks context-length limits by turning long reasoning into iterative, bounded-length thinking.'
authorship: first
keywords:
  - "LLM Reasoning"
  - "Context Management"
  - "Efficient Reasoning"
---

## Abstract

Advanced reasoning in large language models has achieved remarkable performance on challenging tasks, but the prevailing long-context reasoning paradigm faces critical limitations: quadratic computational scaling with sequence length, reasoning constrained by maximum context boundaries, and performance degradation beyond pre-training context windows. Existing approaches primarily compress reasoning chains without addressing the fundamental scaling problem. To overcome these challenges, we introduce InftyThink, a paradigm that transforms monolithic reasoning into an iterative process with intermediate summarization. By interleaving short reasoning segments with concise progress summaries, our approach enables unbounded reasoning depth while maintaining bounded computational costs. This creates a characteristic sawtooth memory pattern that significantly reduces computational complexity compared to traditional approaches. Furthermore, we develop a methodology for reconstructing long-context reasoning datasets into our iterative format, transforming OpenR1-Math into 333K training instances. Experiments across multiple model architectures demonstrate that our approach reduces computational costs while improving performance, with Qwen2.5-Math-7B showing 3-11% improvements across MATH500, AIME24, and GPQA_diamond benchmarks. Our work challenges the assumed trade-off between reasoning depth and computational efficiency, providing a more scalable approach to complex reasoning without architectural modifications.
