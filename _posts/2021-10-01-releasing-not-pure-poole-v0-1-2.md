---
layout: post
title: Learning Stable Matchings with Interviews
author: Amirmahdi Mirfakhar, Xuchuang Wang, Mengfan Xu, Hedyeh Beyhaghi, Mohammad Hajiesmaili 
tags:
- Online_Learning
- Matching_Markets
date: 2021-10-01 13:56 +0800
conf: TBD
abstract: |
Here we study the problem of online learning in competitive two-sided matching markets, Agents \& Firms. In this field of study one/two side/s of the market must learn about their preferences over the other side through a repeated game. Here we want to propose decentralized and coordination-free algorithms that agents can use to reach to their stable matching in structured matching markets. Generally speaking, agents, at each iteration of the game, interact with the other side and build or update a belief about their valuation (preference) over the other side, and then submit it to central algorithm which is guaranteed to find an stable matching regarding the submitted preference lists. At each time step, agents would receive a noisy observation after being matched with another one from the other side. In this work, We try to add one more step of adding the interviews, in which each agent would interview with a subset of agents in the other side, changes his belief about them and submits his preference list over the interviewed set to the central algorithm. The central algorithm, which is assured to find a stable, not necessary complete, matching regarding the submitted preference lists is the \textbf{Gale-Shapley} algorithm.
---
