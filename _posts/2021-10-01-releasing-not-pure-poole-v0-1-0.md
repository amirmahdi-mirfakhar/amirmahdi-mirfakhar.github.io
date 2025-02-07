---
layout: post
title: Heterogenious Multi_Agent Bandits with Parsimonious Hints
author: Amirmahdi Mirfakhar, Xuchuang Wang, Jingang Zuo, Yair Zick, Mohammad Hajiesmaili
tags:
- Online_Learning
- MAB
- Matching_Markets
date: 2021-10-01 13:56 +0800
conf: AAAI_2025
abstract: "We study a hinted heterogeneous multi-agent multi-armed bandits problem (\texttt{HMA2B}), where agents can query low-cost observations (hints) in addition to pulling arms. In this framework, each of the $M$ agents has a unique reward distribution over $K$ arms, and in $T$ rounds, they can observe the reward of the arm they pull only if no other agent pulls that arm.  
The goal is to maximize the total utility by querying the minimal necessary hints without pulling arms, achieving time-independent regret. We study \texttt{HMA2B} in both centralized and decentralized setups. Our main centralized algorithm, \texttt{GP-HCLA}, which is an extension of \texttt{HCLA}, uses a central decision-maker for arm-pulling and hint queries, achieving $O(M^4K)$ regret with $O(MK\log T)$ adaptive hints. In decentralized setups, we propose two algorithms, \texttt{HD-ETC} and \texttt{EBHD-ETC}, that allow agents to choose actions independently through collision-based communication and query hints uniformly until stopping, yielding $O(M^3K^2)$ regret with $O(M^3K\log T)$ hints, where the former requires knowledge of the minimum gap and the latter does not. Finally, we establish lower bounds to prove the optimality of our results and verify them through numerical simulations."
---
