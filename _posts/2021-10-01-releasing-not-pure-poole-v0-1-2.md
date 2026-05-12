---
layout: post
title: Two-Sided Learning in Matching Markets with Interviews
author: Amirmahdi Mirfakhar, Xuchuang Wang, Mengfan Xu, Hedyeh Beyhaghi, Mohammad Hajiesmaili 
tags:
- Online_Learning
- Matching_Markets
date: 2021-10-01 13:56 +0800
link: https://arxiv.org/abs/2602.12224
conf: Arxiv
abstract: |
  Two-sided matching platforms rely on preferences from both sides, yet participants can evaluate only a small fraction of potential partners. In practice, they use low-cost pre-match screening,  e.g., interviews, profile views, or trial tasks, to form noisy impressions before committing to applications and offers. We study bandit learning in matching markets with interviews, modeling these interactions as queried \emph{hints}~\citep{bhaskara2022online} that reveal partial preference information to both sides while constraining subsequent applications. Our framework also allows firm-side uncertainty: firms, like agents, learn their preferences and may make early hiring mistakes. To address this, we introduce strategic deferral, a firm-side action that permits temporary vacancy, corrects premature commitments, and enables decentralized learning under coarse anonymous feedback. We design algorithms for centralized and decentralized markets and show that a constant number of interviews per round suffices for horizon-independent regret, improving over the $O(\log T)$ guarantees known without interviews. Our bounds are near-optimal: the centralized guarantee is within a factor $m$ of an information-theoretic lower bound, while decentralized algorithms match it up to polynomial factors in structured markets and remain horizon-independent in general markets.
--- 
