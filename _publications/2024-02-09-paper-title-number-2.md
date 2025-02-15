---
title: "Towards Gradient-based Bilevel Optimization with Non-convex Followers and Beyonds"
collection: publications
category: conferences
permalink: /publication/2021-09-29-paper-title-number-2
excerpt: 'In recent years, Bi-Level Optimization (BLO) techniques have received extensive attentions from both learning and vision communities. A variety of BLO models in complex and practical tasks are of non-convex follower structure in nature (a.k.a., without Lower-Level Convexity, LLC for short). ...'
date: 2021-09-29
venue: 'Advances in Neural Information Processing Systems 34 (NeurIPS)'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'http://callous-youth.github.io/files/neurips.pdf'
citation: 'Risheng Liu, <strong>Yaohua Liu</strong>, Shangzhi Zeng, Jin Zhang. Towards Gradient-based Bilevel Optimization with Non-convex Followers and Beyond[C]. Advances in Neural Information Processing Systems (NeurIPS), 2021, <span style="color: red;"><strong>Spotlight</strong></span>, <span style="color: red;"><strong>Acceptance Rate ≤ 3% </strong></span>.'
---

In recent years, Bi-Level Optimization (BLO) techniques have received extensive attentions from both learning and vision communities. A variety of BLO models in complex and practical tasks are of non-convex follower structure in nature (a.k.a., without Lower-Level Convexity, LLC for short). However, this challenging class of BLOs is lack of developments on both efficient solution strategies and solid theoretical guarantees. In this work, we propose a new algorithmic framework, named Initialization Auxiliary and Pessimistic Trajectory Truncated Gradient Method (IAPTT-GM), to partially address the above issues. In particular, by introducing an auxiliary as initialization to guide the optimization dynamics and designing a pessimistic trajectory truncation operation, we construct a reliable approximate version of the original BLO in the absence of LLC hypothesis. Our theoretical investigations establish the convergence of solutions returned by IAPTT-GM towards those of the original BLO without LLC. As an additional bonus, we also theoretically justify the quality of our IAPTT-GM embedded with Nesterov’s accelerated dynamics under LLC. The experimental results confirm both the convergence of our algorithm without LLC, and the theoretical findings under LLC.