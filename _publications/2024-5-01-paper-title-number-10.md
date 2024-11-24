---
title: "Advancing Generalized Transfer Attack with Initialization Derived Bilevel Optimization and Dynamic Sequence Truncation"
collection: publications
category: conference
permalink: /publication/2024-05-03-paper-title-number-10
excerpt: 'Transfer attacks generate significant interest for real-world black-box applications by crafting transferable adversarial examples through surrogate models. Whereas, existing works essentially directly optimize the single-level objective w.r.t. the surrogate model, which always leads to poor interpretability of attack mechanism and limited generalization performance over unknown victim models. ...'
date: 2024-10-03
venue: 'Proceedings of the Thirty-Third International Joint Conference on Artificial Intelligence (IJCAI)'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'http://moriyaya.github.io/files/ijcai1.pdf'
citation: 'Yaohua Liu, **Jiaxin Gao**, Xuan Liu, et al. Advancing Generalized Transfer Attack with Initialization Derived Bilevel Optimization and Dynamic Sequence Truncation[J]. arXiv preprint arXiv:2406.02064, 2024.'
---

Transfer attacks generate significant interest for real-world black-box applications by crafting transferable adversarial examples through surrogate models. Whereas, existing works essentially directly optimize the single-level objective w.r.t. the surrogate model, which always leads to poor interpretability of attack mechanism and limited generalization performance over unknown victim models. In this work, we propose the BilEvel Transfer AttacK (BETAK) framework by establishing an initialization derived bilevel optimization paradigm, which explicitly reformulates the nested constraint relationship between the Upper-Level (UL) pseudo-victim attacker and the Lower-Level (LL) surrogate attacker. Algorithmically, we introduce the Hyper Gradient Response (HGR) estimation as an effective feedback for the transferability over pseudo-victim attackers, and propose the Dynamic Sequence Truncation (DST) technique to dynamically adjust the back-propagation path for HGR and reduce computational overhead simultaneously. Meanwhile, we conduct detailed algorithmic analysis and provide convergence guarantee to support non-convexity of the LL surrogate attacker. Extensive evaluations demonstrate substantial improvement of BETAK (e.g., 53.41% increase of attack success rates against IncResv2_ens) against different victims and defense methods in targeted and untargeted attack scenarios. The source code is available at https://github.com/ callous-youth/BETAK.