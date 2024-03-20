---
title: "Vulnerabilities of Foundation Model Integrated Federated Learning Systems Under Adversarial Threats"
collection: publications
permalink: /publication/Vul_FM_FL
authors: <strong>Xi Li</strong>, Chen Wu, and Jiaqi Wang
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
year: 2024
date: 2024-01-17  # Also make sure the date format is correct
venue: 'Under review'
paperurl: '/files/Vul_FMFL.pdf'
citation: 'Xi Li, Chen Wu, and Jiaqi Wang. (2024). "Vulnerabilities of Foundation Model Integrated Federated Learning Systems Under Adversarial Threats."'
header:
  teaser: "Vul_FMFL.png"
---

Federated Learning (FL) addresses critical issues in machine learning related to data privacy and security, yet suffering from data insufficiency and imbalance under certain circumstances.
The emergence of foundation models (FMs) offers potential solutions to the limitations of existing FL frameworks, 
e.g., by generating synthetic data for model initialization.
However, due to the inherent safety concerns of FMs, integrating FMs into FL could introduce new risks, which remains largely unexplored.
To address this gap, we conduct the first investigation on the vulnerability of FM integrated FL (FM-FL) under adversarial threats.
Based on a unified framework of FM-FL, we introduce a novel attack strategy that exploits safety issues of FM to compromise FL client models.
Through extensive experiments with well-known models and benchmark datasets in both image and text domains, we reveal the high susceptibility of the FM-FL  to this new threat under various FL configurations.
Furthermore, we find that existing FL defense strategies offer limited protection against this novel attack approach.
This research highlights the critical need for enhanced security measures in FL  in the era of FMs