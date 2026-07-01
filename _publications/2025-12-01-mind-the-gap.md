---
title: "Mind the Gap: Bridging Thought Leap for Improved Chain-of-Thought Tuning"
collection: publications
category: conferences
permalink: /publication/2025-12-01-mind-the-gap
excerpt: 'Haolei Xu*, <b>Yuchen Yan</b>*, Yongliang Shen, Wenqi Zhang, Guiyang Hou, Shengpei Jiang, Kaitao Song, Weiming Lu, Jun Xiao, Yueting Zhuang (* co-first author)'
date: 2025-12-01
venue: 'NeurIPS 2025'
paperurl: 'https://openreview.net/forum?id=2ogTw5ue7v'
tldr: 'Detects and bridges thought leaps in chains of thought to improve reasoning fine-tuning.'
authorship: cofirst
keywords:
  - "Large Reasoning Models"
  - "LLM Reasoning"
---

## Abstract

Large language models (LLMs) have achieved remarkable progress on mathematical tasks through Chain-of-Thought (CoT) reasoning. However, existing mathematical CoT datasets often suffer from **Thought Leaps** due to experts omitting intermediate steps, which negatively impacts model learning and generalization. We propose the CoT Thought Leap Bridge Task, which aims to automatically detect leaps and generate missing intermediate reasoning steps to restore the completeness and coherence of CoT. To facilitate this, we constructed a specialized training dataset called **ScaleQM+**, based on the structured ScaleQuestMath dataset, and trained **CoT-Bridge** to bridge thought leaps. Through comprehensive experiments on mathematical reasoning benchmarks, we demonstrate that models fine-tuned on bridged datasets consistently outperform those trained on original datasets, with improvements of up to +5.87\% on NuminaMath. Our approach effectively enhances distilled data (+3.02\%) and provides better starting points for reinforcement learning (+3.1\%), functioning as a plug-and-play module compatible with existing optimization techniques. Furthermore, CoT-Bridge demonstrates improved generalization to out-of-domain logical reasoning tasks, confirming that enhancing reasoning completeness yields broadly applicable benefits.
