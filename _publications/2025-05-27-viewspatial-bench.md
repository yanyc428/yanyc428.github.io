---
title: "ViewSpatial-Bench: Evaluating Multi-Perspective Spatial Localization in Vision-Language Models"
collection: publications
category: conferences
permalink: /publication/2025-05-27-viewspatial-bench
excerpt: 'Dingming Li, Hongxing Li, Zixuan Wang, <b>Yuchen Yan</b>, Hang Zhang, Siqi Chen, Guiyang Hou, Shengpei Jiang, Wenqi Zhang, Yongliang Shen, Weiming Lu, Yueting Zhuang'
date: 2025-05-27
venue: 'ECCV 2026'
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-032-37098-3_6'
tldr: 'A benchmark for camera- and human-perspective spatial localization in vision-language models.'
authorship: other
image: "/images/publications/viewspatial-bench.jpg"
image_caption: "ViewSpatial-Bench construction pipeline."
codeurl: 'https://github.com/ZJU-REAL/ViewSpatial-Bench'
projecturl: 'https://zju-real.github.io/ViewSpatial-Page'
keywords:
  - "Spatial Reasoning"
  - "VLM"
  - "Benchmark"
---

## Abstract

Vision-language models (VLMs) have demonstrated remarkable capabilities in understanding and reasoning about visual content, but significant challenges persist in tasks requiring cross-viewpoint understanding and spatial reasoning. We identify a critical limitation: current VLMs excel primarily at egocentric spatial reasoning (from the camera's perspective) but fail to generalize to allocentric viewpoints when required to adopt another entity's spatial frame of reference. We introduce ViewSpatial-Bench, the first comprehensive benchmark designed specifically for multi-viewpoint spatial localization recognition evaluation across five distinct task types, supported by an automated 3D annotation pipeline that generates precise directional labels. Comprehensive evaluation of diverse VLMs on ViewSpatial-Bench reveals a significant performance disparity: models demonstrate reasonable performance on camera-perspective tasks but exhibit reduced accuracy when reasoning from a human viewpoint. By fine-tuning VLMs on our multi-perspective spatial dataset, we achieve an overall performance improvement of 46.24% across tasks, highlighting the efficacy of our approach. Our work establishes a crucial benchmark for spatial intelligence in embodied AI systems and provides empirical evidence that modeling 3D spatial relationships enhances VLMs' corresponding spatial comprehension capabilities.
