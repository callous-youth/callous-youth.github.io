---
title: "Triple-level model inferred collaborative network architecture for video deraining"
collection: publications
category: manuscripts
permalink: /publication/2021-11-30-paper-title-number-8
excerpt: 'Video deraining is an important issue for outdoor vision systems and has been investigated extensively. However, designing optimal architectures by the aggregating model formation and data distribution is a challenging task for video deraining.  ...'
date: 2021-11-30
venue: 'IEEE Transactions on Image Processing (IEEE TIP)'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'http://callous-youth.github.io/files/tip.pdf'
citation: 'Pan Mu, Zhu Liu, <strong>Yaohua Liu</strong>, Risheng Liu, Xin Fan. Triple-level model inferred collaborative network architecture for video deraining[J]. IEEE Transactions on Image Processing (IEEE TIP), 2021, 154: 110558.'
---

Video deraining is an important issue for outdoor vision systems and has been investigated extensively. However, designing optimal architectures by the aggregating model formation and data distribution is a challenging task for video deraining. In this paper, we develop a model-guided triple-level optimization framework to deduce network architecture with cooperating optimization and auto-searching mechanism, named Triple-level Model Inferred Cooperating Searching (TMICS), for dealing with various video rain circumstances. In particular, to mitigate the problem that existing methods cannot cover various rain streaks distribution, we first design a hyper-parameter optimization model about task variable and hyper-parameter. Based on the proposed optimization model, we design a collaborative structure for video deraining. This structure includes Dominant Network Architecture (DNA) and Companionate Network Architecture (CNA) that is cooperated by introducing an Attention-based Averaging Scheme (AAS). To better explore inter-frame information from videos, we introduce a macroscopic structure searching scheme that searches from Optical Flow Module (OFM) and Temporal Grouping Module (TGM) to help restore latent frame. In addition, we apply the differentiable neural architecture searching from a compact candidate set of task-specific operations to discover desirable rain streaks removal architectures automatically. Extensive experiments on various datasets demonstrate that our model shows significant improvements in fidelity and temporal consistency over the state-of-the-art works. Source code is available at https://github.com/vis-opt-group/TMICS.