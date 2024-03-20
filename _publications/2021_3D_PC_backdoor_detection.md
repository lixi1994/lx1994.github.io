---
title: "Detecting Backdoor Attacks Against Point Cloud Classifiers 
v"
collection: publications
permalink: /publication/2021_3D_PC_backdoor_detection
authors: Zhen Xiang, David J. Miller, Siheng Chen, <strong>Xi Li</strong>, and George Kesidis
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
year: 2022
date: 2022-05-22  # Also make sure the date format is correct
venue: 'IEEE International Conference on Acoustics, Speech, and Signal Processing (<strong>ICASSP</strong>)'
paperurl: '/files/2022_ICASSP_3DPC.pdf'
citation: 'Zhen Xiang, David J. Miller, Siheng Chen, Xi Li, and George Kesidis. (2021). "Detecting Backdoor Attacks Against Point Cloud Classifiers." <i>ICASSP</i>.'
header:
  teaser: "ICASSP_3DPC.png"
---

Backdoor attacks (BA) are an emerging threat to deep neural network classifiers. A classifier being attacked will predict to the attacker's target class when a test sample from a source class is embedded with the backdoor pattern (BP). Recently, the first BA against point cloud (PC) classifiers was proposed, creating new threats to many important applications including autonomous driving. Such PC BAs are not detectable by existing BA defenses due to their special BP embedding mechanism. In this paper, we propose a reverse-engineering defense that infers whether a PC classifier is backdoor attacked, without access to its training set or to any clean classifiers for reference. The effectiveness of our defense is demonstrated on the benchmark ModeNet40 dataset for PCs.