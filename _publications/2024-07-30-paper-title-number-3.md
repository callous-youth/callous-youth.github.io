---
title: "Averaged Method of Multipliers for Bi-Level Optimization without Lower-Level Strong Convexity"
collection: publications
category: conferences
permalink: /publication/2023-04-25-paper-title-number-3
excerpt: 'Gradient methods have become mainstream techniques for Bi-Level Optimization (BLO) in learning fields. The validity of existing works heavily rely on either a restrictive Lower- Level Strong Convexity (LLSC) condition or on solving a series of approximation subproblems with high accuracy or both. ...'
date: 2023-04-25
venue: 'International Conference on Machine Learning (ICML)'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
slidesurl: 'https://github.com/callous-youth/sl-BAMM'
citation: 'Risheng Liu, <strong>Yaohua Liu</strong>, Wei Yao, Shangzhi Zeng, Jin Zhang. Averaged Method of Multipliers for Bi-Level Optimization without Lower-Level Strong Convexity[C]. International Conference on Machine Learning (ICML), 2023.'
---

Gradient methods have become mainstream techniques for Bi-Level Optimization (BLO) in learning fields. The validity of existing works heavily rely on either a restrictive Lower- Level Strong Convexity (LLSC) condition or on solving a series of approximation subproblems with high accuracy or both. In this work, by averaging the upper and lower level objectives, we propose a single loop Bi-level Averaged Method of Multipliers (sl-BAMM) for BLO that is simple yet efficient for large-scale BLO and gets rid of the limited LLSC restriction. We further provide non-asymptotic convergence analysis of sl-BAMM towards KKT stationary points, and the comparative advantage of our analysis lies in the absence of strong gradient boundedness assumption, which is always required by others. Thus our theory safely captures a wider variety of applications in deep learning, especially where the upper-level objective is quadratic w.r.t. the lower-level variable. Experimental results demonstrate the superiority of our method.