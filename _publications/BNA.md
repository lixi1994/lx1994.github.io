---
title: "Backdoor Mitigation by Correcting Distribution of Neural activation"
collection: publications
permalink: /publication/BNA
authors: <strong>Xi Li</strong>, Zhen Xiang, David J. Miller, and George Kesidis
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
year: 2023
date: 2023-09-28  # Also make sure the date format is correct
venue: 'Under review'
paperurl: '/files/BNA.pdf'
citation: 'Xi Li, Zhen Xiang, David J. Miller, and George Kesidis. (2022). "Backdoor Mitigation by Correcting Distribution of Neural activation."'
header:
  teaser: "BNA.png"
---

Backdoor (Trojan) attacks are an important type of adversarial exploit against deep neu- ral networks (DNNs), wherein a test instance is (mis)classified to the attacker’s target class whenever the attacker’s backdoor trigger is present. In this paper, we reveal and analyze an important property of backdoor attacks: a successful attack causes an al- teration in the distribution of internal layer activations for backdoor-trigger instances, compared to that for clean instances. Even more importantly, we find that instances with the backdoor trigger will be correctly classified to their original source classes if this distribution alteration is corrected. Based on our observations, we propose an efficient and effective method that achieves post-training backdoor mitigation by correcting the distribution alteration using reverse-engineered triggers. Notably, our method does not change any trainable parameters of the DNN, but achieves generally better mitigation performance than existing methods that do require intensive DNN parameter tuning. It also efficiently detects test instances with the trigger, which may help to catch adversarial entities in the act of exploiting the backdoor.