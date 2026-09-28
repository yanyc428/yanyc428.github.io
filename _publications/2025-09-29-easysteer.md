---
title: "EasySteer: A Unified Framework for High-Performance and Extensible LLM Steering"
collection: publications
category: conferences
permalink: /publication/2025-09-29-easysteer
excerpt: 'Haolei Xu, Xinyu Mei, <b>Yuchen Yan</b>, Rui Zhou, Wenqi Zhang, Weiming Lu, Yueting Zhuang, Yongliang Shen'
date: 2025-09-29
venue: 'EMNLP 2026 (Demo)'
paperurl: 'https://arxiv.org/abs/2509.25175'
tldr: 'A vLLM-based, extensible framework for LLM steering with 10.8-22.3x speedup over existing tools.'
authorship: other
image: "/images/publications/easysteer.png"
image_caption: "Core components of the EasySteer framework."
codeurl: 'https://github.com/ZJU-REAL/EasySteer'
keywords:
  - "LLM Steering"
  - "Inference"
  - "Framework"
---

## Abstract

Large language model (LLM) steering has emerged as a promising paradigm for controlling model behavior at inference time through targeted manipulation of hidden states, offering a lightweight alternative to expensive retraining. However, existing steering frameworks suffer from critical limitations: computational inefficiency, limited extensibility, and restricted functionality that hinder both research progress and practical deployment. We present EasySteer, a unified framework for high-performance, extensible LLM steering built on vLLM. Our system features modular architecture with pluggable interfaces for both analysis-based and learning-based methods, fine-grained parameter control, pre-computed steering vectors for eight application domains, and an interactive demonstration system. Through deep integration with vLLM's optimized inference engine, EasySteer achieves 10.8-22.3 speedup over existing frameworks. Extensive experiments demonstrate its effectiveness in overthinking mitigation, hallucination reduction, and other key applications. EasySteer transforms steering from research technique to production-ready capability, establishing critical infrastructure for deployable, controllable language models.
