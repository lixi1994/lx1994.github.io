---
title: "A Backdoor Attack against 3D Point Cloud Classifiers"
collection: publications
permalink: /publication/2021_3D_PC_backdoor
authors: Zhen Xiang, David J. Miller, Siheng Chen, <strong>Xi Li</strong>, and George Kesidis
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
year: 2021
date: 2021-03-10  # Also make sure the date format is correct
venue: 'International Conference on Computer Vision (<strong>ICCV</strong>)'
paperurl: '/files/2021_ICCV.pdf'
codelink: 'https://github.com/zhenxianglance/PCBA'
citation: 'Zhen Xiang, David J. Miller, Siheng Chen, Xi Li, and George Kesidis. (2022). "A Backdoor Attack against 3D Point Cloud Classifiers." <i>ICCV</i>.'
header:
  teaser: "ICCV.png"
---

Vulnerability of 3D point cloud (PC) classifiers has become a grave concern due to the popularity of 3D sensors in safety-critical applications. Existing adversarial attacks against 3D PC classifiers are all test-time evasion (TTE) attacks that aim to induce test-time misclassifications using knowledge of the classifier. But since the victim classifier is usually not accessible to the attacker, the threat is largely diminished in practice, as PC TTEs typically have poor transferability. Here, we propose the first backdoor attack (BA) against PC classifiers. Originally proposed for images, BAs poison the victim classifier's training set so that the classifier learns to decide to the attacker's target class whenever the attacker's backdoor pattern is present in a given input sample. Significantly, BAs do not require knowledge of the victim classifier. Different from image BAs, we propose to insert a cluster of points into a PC as a robust backdoor pattern customized for 3D PCs. Such clusters are also consistent with a physical attack (i.e., with a captured object in a scene). We optimize the cluster's location using an independently trained surrogate classifier and choose the cluster's local geometry to evade possible PC preprocessing and PC anomaly detectors (ADs). Experimentally, our BA achieves a uniformly high success rate (> 87%) and shows evasiveness against state-of-the-art PC ADs.
