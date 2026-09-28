---
title: "Pause or Fabricate? Training Language Models for Grounded Reasoning"
collection: publications
category: conferences
permalink: /publication/2026-07-03-pause-or-fabricate
excerpt: 'Yiwen Qiu, Linjuan Wu, Yizhou Liu, <b>Yuchen Yan</b>, Jin Ma, Xu Tan, Yao Hu, Daoxin Zhang, Wenqi Zhang, Weiming Lu, Jun Xiao, Yongliang Shen'
date: 2026-07-03
venue: 'ACL 2026 (Findings)'
paperurl: 'https://aclanthology.org/2026.findings-acl.1155/'
tldr: 'Multi-turn RL that teaches models to pause and ask for clarification instead of fabricating missing premises.'
authorship: other
keywords:
  - "Grounded Reasoning"
  - "Hallucination"
  - "Reinforcement Learning"
---

## Abstract

Large language models have achieved remarkable progress on complex reasoning tasks. However, they often implicitly fabricate information when inputs are incomplete, producing confident but unreliable conclusions—a failure mode we term ungrounded reasoning. We argue that this issue arises not from insufficient reasoning capability, but from the lack of inferential boundary awareness—the ability to recognize when the necessary premises for valid inference are missing. To address this issue, we propose Grounded Reasoning via Interactive Reinforcement Learning (GRIL), a multi-turn reinforcement learning framework for grounded reasoning under incomplete information. GRIL decomposes the reasoning process into two stages: clarify and pause, which identifies whether the available information is sufficient, and grounded reasoning, which performs task solving once the necessary premises are established. We design stage-specific rewards to penalize hallucinations, enabling models to detect gaps, stop proactively, and resume reasoning after clarification. Experiments on GSM8K-Insufficient and MetaMATH-Insufficient show that GRIL significantly improves premise detection (up to 45%), leading to a 30% increase in task success while reducing average response length by over 20%. Additional analyses confirm robustness to noisy user responses and generalization to out-of-distribution tasks.
