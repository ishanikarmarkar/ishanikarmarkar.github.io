---
layout: post
title:  "Accelerating data-driven algorithm selection for combinatorial partitioning problems"
image: images/sizegen.png
date: 2025-09-18
categories: research
course: ""  
venue: "NeurIPS Spotlight (top 3% of all submissions)"
authors: "Vaggos Chatziafratis, Ishani Karmarkar, Yingxi Li, and Ellen Vitercik"
subtitle:
---
Data-driven algorithm selection is an approach for choosing effective heuristics for computational problems. It operates by evaluating a set of candidate algorithms on a collection of representative training instances and selecting the one with the best empirical performance. However, running each algorithm on every training instance is computationally expensive, making scalability a central challenge. A practical workaround is to evaluate algorithms on smaller proxy instances derived from the original inputs. We provide the first theoretical foundations for this practice by formalizing the notion of size generalization: predicting an algorithm's performance on a large instance by evaluating it on a smaller, representative instance, subsampled from the original instance. We provide size generalization guarantees for several clustering algorithms and max-cut algorithms.
