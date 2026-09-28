---
title: "Double-Checker: Enhancing Reasoning of Slow-Thinking LLMs via Self-Critical Fine-Tuning"
collection: publications
category: preprints
permalink: /publication/2025-06-26-double-checker
excerpt: 'Xin Xu, Tianhao Chen, Fan Zhang, Wanlong Liu, Pengxiang Li, Ajay Kumar Jaiswal, <b>Yuchen Yan</b>, Jishan Hu, Yang Wang, Hao Chen, Shiwei Liu, Shizhe Diao, Can Yang, Lu Yin'
date: 2025-06-26
venue: 'Under Review'
paperurl: 'https://arxiv.org/abs/2506.21285'
tldr: 'Fine-tunes long-CoT models to iteratively critique and refine their own solutions.'
authorship: other
keywords:
  - "Self-Critique"
  - "Long CoT"
  - "LLM Reasoning"
---

## Abstract

While slow-thinking large language models (LLMs) exhibit reflection-like reasoning, commonly referred to as the "aha moment", their ability to generate informative critiques and refine prior solutions remains limited. In this paper, we introduce Double-Checker, a principled framework designed to enhance the reasoning capabilities of slow-thinking LLMs by fostering explicit self-critique and iterative refinement of their previous solutions. By fine-tuning on our curated 1,730 self-critical instances, Double-Checker empowers long-CoT LLMs to iteratively critique and refine their outputs during inference until they evaluate their solutions as correct under self-generated critiques. We validate the efficacy of Double-Checker across a comprehensive suite of reasoning benchmarks, demonstrating that iterative self-critique significantly enhances the reasoning capabilities of long-CoT LLMs. Notably, our Double-Checker increases the pass@1 performance on challenging AIME benchmarks from 4.4% to 18.2% compared to the original long-CoT LLMs. These results highlight a promising direction for developing more trustworthy and effective LLMs capable of structured self-critique. Our codes and data are available at https://github.com/XinXU-USTC/DoubleChecker
