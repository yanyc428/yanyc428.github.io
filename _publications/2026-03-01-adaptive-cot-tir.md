---
title: "Teaching LLMs According to Their Aptitude: Adaptive Switching Between CoT and TIR for Mathematical Problem Solving"
collection: publications
category: conferences
permalink: /publication/2026-03-01-adaptive-cot-tir
excerpt: 'Xin Xu, Yan Xu, Tianhao Chen, <b>Yuchen Yan</b>, Chengwu Liu, Zaoyu Chen, Yufei Wang, Yichun Yin, Yasheng Wang, Qun Liu, Lu Yin'
date: 2026-03-01
venue: 'CPAL 2026 (Oral)'
paperurl: 'https://openreview.net/forum?id=8PWIyOSSVP'
tldr: 'Adaptively switches between chain-of-thought and tool-integrated reasoning based on problem difficulty.'
authorship: other
keywords:
  - "Large Language Models"
  - "math QA"
  - "chain-of-thought"
  - "tool-integrated reasoning"
  - "fine-tuning"
---

## Abstract

Existing supervised fine-tuning (SFT) approaches to enhance the mathematical reasoning of large language models (LLMs) rely either on Chain-of-Thought (CoT) for generalizability or Tool-Integrated Reasoning (TIR) for precise computation. While efforts have been made to combine these methods, they primarily rely on post-selection or predefined strategies, leaving an open question: Could we endow LLMs with the ability to adaptively determine whether to use CoT or TIR based on the math problems at hand before decoding? In this work, we propose TATA (Teaching LLMs According to Their Aptitude), an adaptive framework that enables LLMs to personalize their reasoning strategy for different problems spontaneously, aligning it with their intrinsic aptitude. TATA incorporates base-LLM-aware data selection during SFT to tailor training data to the model’s unique abilities, which equips LLMs to autonomously determine and apply the effective reasoning strategy at test time. Empirical results demonstrate that TATA effectively combines the complementary strengths of CoT and TIR, achieving superior or comparable performance with improved inference efficiency compared to existing methods. Further analysis highlights the crucial role of aptitude-aware data selection in enabling LLMs to make informed and adaptive reasoning decisions, aligning reasoning strategies with model capabilities.
