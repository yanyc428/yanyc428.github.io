---
title: "Milestone-Guided Policy Learning for Long-Horizon Language Agents"
collection: publications
category: conferences
permalink: /publication/2026-07-02-milestone-policy
excerpt: 'Zixuan Wang, <b>Yuchen Yan</b>, Hongxing Li, Teng Pan, Dingming Li, Ruiqing Zhang, Weiming Lu, Jun Xiao, Yueting Zhuang, Yongliang Shen'
date: 2026-07-02
venue: 'ICML 2026'
paperurl: 'https://openreview.net/forum?id=Ga3AR4EF6R'
tldr: 'Guides long-horizon language agents with milestone signals to make policy learning more stable.'
authorship: other
keywords:
  - "Large Language Model Agents"
  - "Reinforcement Learning"
  - "Policy Optimization"
  - "Credit Assignment"
---

## Abstract

While long-horizon agentic tasks require language agents to perform dozens of sequential decisions, training such agents with reinforcement learning remains challenging. We identify two root causes: credit misattribution, where correct early actions are penalized due to terminal failures, and sample inefficiency, where scarce successful trajectories result in near-total loss of learning signal. We introduce a milestone-guided policy learning framework, BEACON, that leverages the compositional structure of long-horizon tasks to ensure precise credit assignment. BEACON partitions trajectories at milestone boundaries, applies temporal reward shaping within segments to credit partial progress, and estimates advantages at dual scales to prevent distant failures from corrupting the evaluation of local actions. On ALFWorld, WebShop, and ScienceWorld, BEACON consistently outperforms GRPO and GiGPO. Notably, on long-horizon ALFWorld tasks, BEACON achieves 92.9\% success rate, nearly doubling GRPO's 53.5\%, while improving effective sample utilization from 23.7\% to 82.0\%. These results establish milestone-anchored credit assignment as an effective paradigm for training long-horizon language agents. Code is in supplementary materials and will be publicly released.
