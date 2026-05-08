---
layout: post
title: Efficient Online Proportional Sampling with Applications to Smoothed Online Learning
author:  Amirmahdi Mirfakhar, Nina Balcan, Hedyeh Beyhaghi
tags:
- Online_Learning
- Data_Structures
date: 2021-10-01 13:56 +0800
conf: Arxiv
abstract: |
  We study the problem of efficient online proportional sampling from a high-dimensional domain under a $\sigma$-smoothed adversary, where the sampling distribution is induced by a dynamically evolving weight function defined over a sequence of piecewise-structured partitions. This setting captures a broad range of applications,
including principal-agent games (e.g., pricing and contract design), and algorithm configuration and parameter tuning. The central challenge is maintaining an efficient data structure as the induced partition grows increasingly complex over time---naively, the number of subregions can grow as $O(t^d)$ by round $t$ in $d$ dimensions. We design a data structure that supports efficient updates and proportional sampling while avoiding the cost of explicitly maintaining this exponential growth, where the discontinuities are structured from axis-parallel hyperplanes. Under a $\sigma$-smoothed adaptive adversary, we prove a tight $O(\sqrt{\sigma T})$ bound on the depth of our data structure, and an $O(\log T)$ bound under a random-order adversary---to our knowledge, the first such results for this class of problems. We apply this framework to online learning with piecewise-structured rewards, obtaining efficient no-regret algorithms under both full-information and bandit feedback, with provable sublinear regret guarantees.
---
