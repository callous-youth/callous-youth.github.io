---
title: "Past as Prior: Reweighted Proxy Guidance for Stable Adversarial Training"
collection: publications
category: conferences
permalink: /publication/2026-05-06-past-as-prior
excerpt: 'Adversarial training often suffers from unstable convergence, large variance, and catastrophic overfitting. RPG treats the immediately preceding model as a history-driven prior to steer updates toward more robust solutions. ...'
date: 2026-05-06
venue: 'IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)'
paperurl: 'http://callous-youth.github.io/files/icassp2026_past_as_prior.pdf'
citation: '<strong>Yaohua Liu</strong>, Jiaxin Gao. Past as Prior: Reweighted Proxy Guidance for Stable Adversarial Training[C]. IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), 2026, pp. 3356-3360.'
---

Adversarial robustness is critical for the reliable deployment of deep neural networks in safety-sensitive applications, with adversarial training (AT) being the dominant defense technique. However, existing AT methods still suffer from unstable convergence, large variance, and catastrophic overfitting. To alleviate these limitations, this work proposes Reweighted Proxy Guidance (RPG), which treats the immediately preceding model as a history-driven prior to steer updates toward more robust solutions. At its core, a Reweighted Differential Unit (RDU) forms a reweighted differential between the current parameters and a proxy-induced response, providing a flexible update rule compatible with both single-step and multi-step AT. It further introduces a teacher-free self-distillation defense objective aligned with the proxy to regularize the learning trajectory and mitigate catastrophic overfitting.
