---
title: Flipover to bolster model robustness
summary: We proposed flipover, an new approach not only serves as a more effective regularization technique than conventional dropout, mitigating overfitting, but also introduces adversarial perturbations to gradients, enhancing resilience against adversairal attacks.
tags:
  - Deep Leaning
date: '2023-12-23T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: ''
  focal_point: Smart

---

**Abstract**: Flipover, an enhanced dropout technique, is introduced to improve the robustness of artificial neural networks. In contrast to dropout, which involves randomly removing certain neurons and their connections, flipover randomly selects neurons and reverts their outputs using a negative multiplier during training. This approach offers stronger regularization than conventional dropout, refining model performance by (1) mitigating overfitting, matching or even exceeding the efficacy of dropout; (2) amplifying robustness to noise; and (3) enhancing resilience against adversarial attacks. Extensive experiments across various neural networks affirm the effectiveness of flipover in deep learning.
