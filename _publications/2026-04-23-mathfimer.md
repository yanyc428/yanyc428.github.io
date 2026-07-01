---
title: "MathFimer: Enhancing Mathematical Reasoning by Expanding Reasoning Steps through Fill-in-the-Middle Task"
collection: publications
category: conferences
permalink: /publication/2026-04-23-mathfimer
excerpt: '<b>Yuchen Yan</b>, Yongliang Shen, Yang Liu, Jin Jiang, Xin Xu, Mengdi Zhang, Jian Shao, Yueting Zhuang (&dagger; first author)'
date: 2026-04-23
venue: 'ICLR 2026'
paperurl: 'https://openreview.net/forum?id=14i2wzPPfn'
tldr: 'Expands reasoning chains via a fill-in-the-middle task to strengthen mathematical reasoning.'
authorship: first
keywords:
  - "LLM Reasoning"
  - "Mathematical Reasoning"
  - "Data Augmentation"
---

## Abstract

Mathematical reasoning represents a critical frontier in advancing large language models (LLMs). While step-by-step approaches have emerged as the dominant paradigm for mathematical problem-solving in LLMs, the quality of reasoning steps in training data fundamentally constrains the performance of the models. Recent studies have demonstrated that more detailed intermediate steps can enhance model performance, yet existing methods for step expansion either require more powerful external models or incur substantial computational costs. In this paper, we introduce MathFimer, a novel framework for mathematical reasoning step expansion inspired by the ''Fill-in-the-middle'' task from code reasoning. By decomposing solution chains into prefix-suffix pairs and training models to reconstruct missing intermediate steps, we develop a specialized model, MathFimer-7B, on our carefully curated NuminaMath-FIM dataset. We then apply these models to enhance existing mathematical reasoning datasets by inserting detailed intermediate steps into their solution chains, creating MathFimer-expanded versions. Through comprehensive experiments on multiple mathematical reasoning datasets, including MathInstruct, MetaMathQA and etc., we demonstrate that models trained on MathFimer-expanded data consistently outperform their counterparts trained on original data across various benchmarks such as GSM8K and MATH. Our approach offers a practical, scalable solution for enhancing mathematical reasoning capabilities in LLMs without relying on powerful external models or expensive inference procedures.
