---
title: "Test-Time Reinforcement Learning for GUI Grounding via Region Consistency"
collection: publications
category: conferences
permalink: /publication/2026-01-15-gui-grounding-ttrl
excerpt: 'Yong Du*, <b>Yuchen Yan</b>*, Fei Tang, Zhengxi Lu, Chang Zong, Weiming Lu, Shengpei Jiang, Yongliang Shen (* co-first author)'
date: 2026-01-15
venue: 'AAAI 2026'
paperurl: 'https://openreview.net/forum?id=WHiAkFjwya'
tldr: 'Improves GUI grounding at test time via label-free region-consistency reinforcement learning.'
authorship: cofirst
keywords:
  - "GUI Agents"
  - "Test-Time RL"
  - "Visual Grounding"
---

## Abstract

Graphical User Interface (GUI) grounding, the task of mapping natural language instructions to precise screen coordinates, is fundamental to autonomous GUI agents. While existing methods achieve strong performance through extensive supervised training or reinforcement learning with labeled rewards, they remain constrained by the cost and availability of pixel-level annotations. We observe that when models generate multiple predictions for the same GUI element, the spatial overlap patterns reveal implicit confidence signals that can guide more accurate localization. Leveraging this insight, GUI-RC (Region Consistency), a test-time scaling method that constructs spatial voting grids from multiple sampled predictions to identify consensus regions where models show highest agreement. Without any training, GUI-RC improves accuracy by 2-3% across various architectures on ScreenSpot benchmarks. We further introduce GUI-RCPO (Region Consistency Policy Optimization), transforming these consistency patterns into rewards for test-time reinforcement learning. By computing how well each prediction aligns with the collective consensus, GUI-RCPO enables models to iteratively refine their outputs on unlabeled data during inference. Extensive experiments demonstrate the generality of our approach: using only 1,272 unlabeled data, GUI-RCPO achieves 3-6% accuracy improvements across various architectures on ScreenSpot benchmarks. Our approach reveals the untapped potential of test-time scaling and test-time reinforcement learning for GUI grounding, offering a promising path toward more data-efficient GUI agents.
