---
title:          "AdaptFuse: Training-Free Sequential Preference Inference via Externalized Bayesian Computation"
date:           2026-04-05 00:01:00 +0800
selected:       true
pinned:         true
pub:            "arXiv preprint"
pub_date:       "2026"

abstract: >-
  LLMs struggle to accumulate evidence across multiple rounds of user interaction in a manner consistent with Bayesian inference. We propose AdaptFuse, a training-free framework that externalizes probabilistic computation from the LLM: a symbolic module maintains a Bayesian posterior over a discrete hypothesis set, while a frozen LLM contributes semantic reasoning via multi-sample Dirichlet aggregation, and the two are combined through entropy-adaptive fusion. Across flight recommendation, hotel recommendation, and web shopping, AdaptFuse consistently outperforms both prompting baselines and fine-tuned Bayesian Teaching models, without storing or training on sensitive user data.
cover:          /assets/images/covers/adaptfuse.png
authors:
  - Fangzhou Lin*
  - Zilin Dai*
  - Shuo Xing
  - Peiran Li
  - Siyuan Yang
  - Qianwen Ge
  - Kazunori Yamada
  - Yang Zhou
  - Ziming Zhang
  - Haichong Zhang
  - Zhengzhong Tu
links:
  Paper: https://arxiv.org/abs/2604.03925
---
