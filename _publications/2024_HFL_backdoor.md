---
title: "Unveiling Backdoor Risks Brought by Foundation Models in Heterogeneous Federated Learning"
collection: publications
permalink: /publication/2024_HFL_backdoor
authors: <strong>Xi Li</strong>, Chen Wu, and Jiaqi Wang
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
year: 2024
date: 2024-01-27  # Also make sure the date format is correct
venue: 'The 28th Pacific-Asia Conference on Knowledge Discovery and Data Mining (<strong>PAKDD</strong>)'
paperurl: '/files/BD_HFL.pdf'
codelink: 'https://github.com/lixi1994/backdoor_FM_hete_FL'
citation: 'Xi Li, Chen Wu, and Jiaqi Wang. (2024). "Unveiling Backdoor Risks Brought by Foundation Models in Heterogeneous Federated Learning." <i>PAKDD</i>.'
header:
  teaser: "BD_HFL.png"
---

The foundation models (FMs) have been used to generate synthetic public datasets for the heterogeneous federated learning (HFL) problem where each client uses a unique model architecture.
However, the vulnerabilities of integrating FMs, especially against backdoor attacks, are not well-explored in the HFL contexts. In this paper, we introduce a novel backdoor attack mechanism for HFL that circumvents the need for client compromise or ongoing participation in the FL process. 
This method plants and transfers the backdoor through a generated synthetic public dataset, which could help evade existing backdoor defenses in FL by presenting normal client behaviors. 
Empirical experiments across different HFL configurations and benchmark datasets demonstrate the effectiveness of our attack compared to traditional client-based attacks. 
Our findings reveal significant security risks in developing robust FM-assisted HFL systems. 
This research contributes to enhancing the safety and integrity of FL systems, highlighting the need for advanced security measures in the era of FMs.
