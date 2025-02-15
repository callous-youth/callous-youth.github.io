---
title: "Advancing Generalized Transfer Attack with Initialization Derived Bilevel Optimization and Dynamic Sequence Truncation"
collection: publications
category: conferences
permalink: /publication/2024-10-28-paper-title-number-4
excerpt: 'Transfer attacks generate significant interest for real-world black-box applications by crafting transferable adversarial examples through surrogate models. Whereas, existing works essentially directly optimize the single-level objective w.r.t. the surrogate model, which always leads to poor interpretability of attack mechanism and limited generalization performance over unknown victim models. ...'
date: 2024-10-28
venue: 'International Joint Conference on Artificial Intelligence (IJCAI)'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'http://callous-youth.github.io/files/jicai.pdf'
citation: '<strong>Yaohua Liu</strong>, Jiaxin Gao, Xuan Liu, Xianghao Jiao, Xin Fan, Risheng Liu. Advancing Generalized Transfer Attack with Initialization Derived Bilevel Optimization and Dynamic Sequence Truncation[C]. International Joint Conference on Artificial Intelligence (IJCAI), 2024.'
---

Transfer attacks generate significant interest for real-world black-box applications by crafting transferable adversarial examples through surrogate models. Whereas, existing works essentially directly optimize the single-level objective w.r.t. the surrogate model, which always leads to poor interpretability of attack mechanism and limited generalization performance over unknown victim models. In this work, we propose the BilEvel Transfer AttacK (BETAK) framework by establishing an initialization derived bilevel optimization paradigm, which explicitly reformulates the nested constraint relationship between the Upper-Level (UL) pseudo-victim attacker and the Lower-Level (LL) surrogate attacker. Algorithmically, we introduce the Hyper Gradient Response (HGR) estimation as an effective feedback for the transferability over pseudo-victim attackers, and propose the Dynamic Sequence Truncation (DST) technique to dynamically adjust the back-propagation path for HGR and reduce computational overhead simultaneously. Meanwhile, we conduct detailed algorithmic analysis and provide convergence guarantee to support non-convexity of the LL surrogate attacker. Extensive evaluations demonstrate substantial improvement of BETAK (e.g., 53.41% increase of attack success rates against IncRes-v2_ens victim) against different victims and defense methods in targeted and untargeted attack scenarios.