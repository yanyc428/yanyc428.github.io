---
title: "Learning from Reliable Negatives: Confidence-Anchored Test-Time Adaptation for GUI Grounding"
collection: publications
category: conferences
permalink: /publication/2026-09-08-canl-gui-grounding
excerpt: 'Yizhou Liu, Fei Tang, <b>Yuchen Yan</b>, Zhengxi Lu, Songqin Nong, Tao Jiang, Wenhao Xu, Wenqi Zhang, Weiming Lu, Jun Xiao, Yongliang Shen'
date: 2026-09-08
venue: 'ECCV 2026'
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-032-37029-7_14'
tldr: 'Label-free test-time adaptation for GUI grounding that learns from reliable negative samples anchored by coordinate-token confidence.'
authorship: other
image: "/images/publications/canl-gui-grounding.jpg"
image_caption: "The CANL pipeline."
keywords:
  - "GUI Agent"
  - "GUI Grounding"
  - "Test-Time Training"
---

## Abstract

Graphical User Interface (GUI) grounding is essential for autonomous agents to map natural language instructions to precise screen coordinates. However, existing supervised fine-tuning and reinforcement learning methods are constrained by the high cost of annotation, creating a scalability bottleneck. In this paper, we introduce a label-free test-time training paradigm driven by two key insights: (1) confidence patterns in coordinate tokens are a better indicator than full-sequence confidence, and (2) in sparse GUI coordinate spaces, negative samples offer more reliable learning signals than potentially noisy positive ones. We first propose Confidence-Anchored Learning (CAL), which utilizes coordinate-token confidence to filter pseudo-labels and assign distance-based binary rewards. Building on this, we develop Confidence-Anchored Negative Learning (CANL), which exclusively optimizes the model using negative samples to bypass the risks of incorrect positive samples. Experimental results demonstrate that CANL-7B achieves 92.1% on ScreenSpot-V2. On more challenging ScreenSpot-Pro, CANL-7B reaches 33.8%, an 8.9% absolute improvement over the base model. Our findings establish coordinate-token confidence as a powerful alternative to manual annotations for scalable GUI agent development.
