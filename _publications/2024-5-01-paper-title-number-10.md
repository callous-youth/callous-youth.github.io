---
title: "Motion-Scenario Decoupling for Rat-Aware Video Position Prediction: Strategy and Benchmark"
collection: publications
category: conferences
permalink: /publication/2023-10-30-paper-title-number-10
excerpt: 'Recently significant progress has been made in human action recognition and behavior prediction using deep learning techniques, leading to improved vision-based semantic understanding. However, there is still a lack of high-quality motion datasets for small bio-robotics, which presents more challenging scenarios for long-term movement prediction and behavior control based on third-person observation. ...'
date: 2023-10-30
venue: 'International Conference on Image and Graphics (ICIG)'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'http://callous-youth.github.io/files/ICIG.pdf'
citation: 'Xiaofeng Liu, Jiaxin Gao, <strong>Yaohua Liu</strong>, et al. Motion-Scenario Decoupling for Rat-Aware Video Position Prediction: Strategy and Benchmark[C]. International Conference on Image and Graphics (ICIG), 2023, <strong>Oral</strong>.'
---

Recently significant progress has been made in human action recognition and behavior prediction using deep learning techniques, leading to improved vision-based semantic understanding. However, there is still a lack of high-quality motion datasets for small bio-robotics, which presents more challenging scenarios for long-term movement prediction and behavior control based on third-person observation. In this study, we introduce RatPose, a bio-robot motion prediction dataset constructed by considering the influence factors of individuals and environments based on predefined annotation rules. To enhance the robustness of motion prediction against these factors, we propose a Dual-stream Motion-Scenario Decoupling (DMSD) framework that effectively separates scenario-oriented and motion-oriented features and designs a scenario contrast loss and motion clustering loss for overall training. With such distinctive architecture, the dual-branch feature flow information is interacted and compensated in a decomposition-then-fusion manner. Moreover, we demonstrate significant performance improvements of the proposed DMSD framework on different difficulty-level tasks. We also implement long-term discretized trajectory prediction tasks to verify the generalization ability of the proposed dataset.