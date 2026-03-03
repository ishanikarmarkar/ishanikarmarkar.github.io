---
layout: post
title:  "Reusing Samples in Variance-Reduction"
image: images/reuse-samples.png
date: 2026-01-01
categories: research
course: ""  
venue: "Algorithmic Learning Theory (ALT) | <span style='border: 2px solid red; padding: 2px 6px; border-radius: 4px;'>Most Elegant Paper Award</span>"
authors: "Yujia Jin, Ishani Karmarkar, Aaron Sidford, and Jiayi Wang"
subtitle:
---
We provide a general framework to improve trade-offs between the number of _full batch_ and _sample queries used to solve structured optimization problems. Our results apply to a broad class of randomized optimization algorithms that iteratively solve sub-problems to high accuracy. We show that such algorithms can be modified to reuse the randomness used to query the input across sub-problems. Consequently, we improve the trade-off between the number of gradient (full batch) and individual function (sample) queries for finite sum minimization, the number of matrix-vector multiplies (full batch) and random row (sample) queries for top-eigenvector computation, and the number of matrix-vector multiplies with the transition matrix (full batch) and generative model (sample) queries for optimizing Markov Decision Processes. (<a href="https://arxiv.org/abs/2509.02526">arxiv</a>)