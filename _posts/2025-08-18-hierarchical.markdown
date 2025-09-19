---
layout: post
title:  "Mean-Field Sampling for Cooperative Multi-Agent Reinforcement Learning"
image: images/star.png
date: 2025-09-18
categories: research
course: ""  
venue: "NeurIPS Spotlight (top 3% of all submissions) | Best Paper at AAAI Workshop on Multi-Agents in the Real World (MARL)"
authors: "Emile Timothy Anand, Ishani Karmarkar, and Gunnan Qu"
subtitle:
---

Designing efficient algorithms for multi-agent reinforcement learning (MARL) is fundamentally challenging because the size of the joint state and action spaces grows exponentially in the number of agents. These difficulties are exacerbated when balancing sequential global decision-making with local agent interactions. In this work, we propose a new algorithm and a decentralized randomized policy for a system with $n$ agents. For any $k\leq n$, our algorithm learns a policy for the system in time polynomial in $k$. We prove that this learned policy converges to the optimal policy on the order of $\smash{\tilde{O}(1/\sqrt{k})}$ as the number of subsampled agents $k$ increases. (<a href="https://arxiv.org/abs/2412.00661">arxiv</a>)