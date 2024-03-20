---
title: "Backdoor Threats from Compromised Foundation Models to Federated Learning"
collection: publications
permalink: /publication/2023_FMFL_backdoor
authors: <strong>Xi Li</strong>, Songhe Wang, Chen Wu, Hao Zhou, and Jiaqi Wang
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
year: 2023
date: 2023-10-27  # Also make sure the date format is correct
venue: 'International Workshop on FL@FM in Conjunction with NeurIPS 2023 (<strong>FL@FM-NeurIPS’23</strong>)'
paperurl: '/files/backdoor_FMFL.pdf'
posterlink: '/files/backdoor_FMFL_poster.pdf'
codelink: 'https://github.com/lixi1994/backdoor_FM_FL'
citation: 'Xi Li, Songhe Wang, Chen Wu, Hao Zhou, and Jiaqi Wang. (2023). "Backdoor Threats from Compromised Foundation Models to Federated Learning." <i>FL@FM-NeurIPS’23</i>.'
header:
  teaser: "backdoor_FMFL.png"
---

Federated learning (FL) represents a novel paradigm to machine learning, addressing critical issues related to data privacy and security, yet suffering from data insufficiency and imbalance.
The emergence of foundation models (FMs) provides a promising solution to the problems with FL.
For instance, FMs could serve as teacher models or good starting points for FL.
However, the integration of FM in FL presents a new challenge, exposing the FL systems to potential threats. 
This paper investigates the robustness of FL incorporating FMs by assessing their susceptibility to backdoor attacks.
Contrary to classic backdoor attacks against FL, the proposed attack (1) does not require the attacker \textit{fully} involved in the FL process; (2) poses a significant risk in practical FL scenarios; (3) is able to evade existing robust FL frameworks/ FL backdoor defenses; (4) underscores the researches on the robustness of FL systems integrated with FMs.
The effectiveness of the proposed attack is demonstrated by extensive experiments with various well-known models and benchmark datasets encompassing both text and image classification domains. 
