---
title: "Machine Learning-Enhanced Ant Colony Optimization for Column Generation"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2009-10-01
venue: 'GECCO 24'
slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'http://academicpages.github.io/files/paper1.pdf'
citation: ''
---

Column generation (CG) is a powerful technique for solving optimization problems that involve a large number of variables or columns. This technique begins by solving a smaller problem with a subset of columns and gradually generates additional columns as needed. However, the generation of columns often requires solving difficult subproblems repeatedly, which can be a bottleneck for CG. To address this challenge, we propose a novel method called machine learning enhanced ant colony optimization (MLACO), to efficiently generate multiple high-quality columns from a sub-problem. Specifically, we train a ML model to predict the optimal solution of a subproblem, and then integrate this ML prediction into the probabilistic model of ACO to sample multiple high-quality columns. Our experimental results on the bin packing problem with conflicts show that the MLACO method significantly improves the performance of CG compared to several state-of-the-art methods. Furthermore, when our method is incorporated into a Branch-and-Price method, it leads to a significant reduction in solution time.
