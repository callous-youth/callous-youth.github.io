---
title: "Investigating Bi-Level Optimization for Learning and Vision From a Unified Perspective: A Survey and Beyond"
collection: publications
category: manuscripts
permalink: /publication/2021-12-06-paper-title-number-1
excerpt: 'Bi-Level Optimization (BLO) is originated from the area of economic game theory and then introduced into the optimization community. BLO is able to handle problems with a hierarchical structure, involving two levels of optimization tasks, where one task is nested inside the other. ...'
date: 2021-12-06
venue: 'IEEE Transactions on Pattern Analysis and Machine Intelligence (IEEE TPAMI)'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'http://moriyaya.github.io/files/tpami1.pdf'
citation: 'Risheng Liu, <strong>Jiaxin Gao</strong>, Jin Zhang, et al. Investigating bi-level optimization for learning and vision from a unified perspective: A survey and beyond[J]. IEEE Transactions on Pattern Analysis and Machine Intelligence, 2021, 44(12): 10045-10067.'
---

Bi-Level Optimization (BLO) is originated from the area of economic game theory and then introduced into the optimization community. BLO is able to handle problems with a hierarchical structure, involving two levels of optimization tasks, where one task is nested inside the other. In machine learning and computer vision fields, despite the different motivations and mechanisms, a lot of complex problems, such as hyper-parameter optimization, multi-task and meta learning, neural architecture search, adversarial learning and deep reinforcement learning, actually all contain a series of closely related subproblms. In this paper, we first uniformly express these complex learning and vision problems from the perspective of BLO. Then we construct a best-response-based single-level reformulation and establish a unified algorithmic framework to understand and formulate mainstream gradient-based BLO methodologies, covering aspects ranging from fundamental automatic differentiation schemes to various accelerations, simplifications, extensions and their convergence and complexity properties. Last but not least, we discuss the potentials of our unified BLO framework for designing new algorithms and point out some promising directions for future research. A list of important papers discussed in this survey, corresponding codes, and additional resources on BLOs are publicly available at: https://github.com/vis-opt-group/BLO.