---
title: "Augmenting Iterative Trajectory for Bilevel Optimization: Methodology, Analysis and Extensions"
collection: publications
category: manuscripts
permalink: /publication/2025-12-5-paper-title-number-11
excerpt: 'Abstract—In recent years, there has been a surge of machine learning applications developed with hierarchical structure, which can be approached from Bi-Level Optimization (BLO) perspective. However, most existing gradient-based methods overlook the interdependence between hyper-gradient calculation and Lower-Level (LL) iterative trajectory, focusing solely on the former. Consequently, convergence theory is constructed with restrictive LL assumptions, which are often challenging to satisfy in real-world scenarios. In this work, ...'
date: 2025-12-5
venue: 'Transactions on Pattern Analysis and Machine Intelligence (IEEE TPAMI)'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'http://callous-youth.github.io/files/tpami1.pdf'
slidesurl: 'https://github.com/callous-youth/IAPTT-GM'
citation: 'Risheng Liu, <strong>Yaohua Liu</strong>, Shangzhi Zeng, Jin Zhang. Augmenting Iterative Trajectory for Bilevel Optimization: Methodology, Analysis and Extensions[J]. Transactions on Pattern Analysis and Machine Intelligence (IEEE TPAMI), 2025.'
---

In recent years, there has been a surge of machine learning applications developed with hierarchical structure, which can be approached from Bi-Level Optimization (BLO) perspective. However, most existing gradient-based methods overlook the interdependence between hyper-gradient calculation and Lower-Level (LL) iterative trajectory, focusing solely on the former. Consequently, convergence theory is constructed with restrictive LL assumptions, which are often challenging to satisfy in real-world scenarios. In this work, we thoroughly analyze the constructed iterative trajectory, and highlight two deficiencies, including empirically chosen initialization and default use of entire trajectory for hyper-gradient calculation. To address these issues, we introduce two augmentation techniques including Initialization Auxiliary (IA) and Pessimistic Trajectory Truncation (PTT), and investigate various extension strategies such as prior regularization, different iterative mapping schemes and acceleration dynamics to construct Augmented Iterative Trajectory (AIT) for corresponding BLO scenarios (e.g., LL convexity and LL non-convexity). Theoretically, we provide convergence analysis for AIT and its variations under different LL assumptions, and establish the convergence analysis for BLOs with non-convex LL subproblem. Finally, we demonstrate the effectiveness of AIT through three numerical examples, typical learning and vision applications (e.g., data hyper-cleaning and few-shot learning) and more challenging tasks such as neural architecture search.
		