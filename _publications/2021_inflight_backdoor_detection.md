---
title: "Test-Time Detection of Backdoor Triggers of Poisoned Deep Neural Networks "
collection: publications
permalink: /publication/2021_inflight_backdoor_detection
authors: <strong>Xi Li</strong>, David J. Miller, Zhen Xiang, and George Kesidis
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
year: 2022
date: 2022-05-22  # Also make sure the date format is correct
venue: 'IEEE International Conference on Acoustics, Speech, and Signal Processing (<strong>ICASSP</strong>)'
paperurl: '/files/2022_ICASSP_in_flight.pdf'
posterlink: '/files/ICASSP_in_flight_poster.pdf'
citation: 'Xi Li, David J. Miller, Zhen Xiang, and George Kesidis. (2022). "Test-Time Detection of Backdoor Triggers of Poisoned Deep Neural Networks." <i>ICASSP</i>.'
header:
  teaser: "ICASSP_in_flight.png"
---

Backdoor (Trojan) attacks are emerging threats against deep neural networks (DNN). A DNN being attacked will predict to an attacker-desired target class whenever a test sample from any source class is embedded with a backdoor pattern, while correctly classifying clean (attack-free) test samples.
Existing backdoor defenses have shown success in detecting whether a DNN is attacked and in reverse-engineering the backdoor pattern in a "post-training" scenario: the defender has access to the DNN to be inspected and a small, clean dataset collected independently, but has no access to the (possibly poisoned) training set of the DNN. 
However, these defenses neither catch culprits in the act of triggering the backdoor mapping, nor mitigate the backdoor attack at test-time. In this paper, we propose an "in-flight" unsupervised defense against backdoor attacks on image classification that 1) detects use of a backdoor trigger at test-time; and 2) infers the class of origin (source class) for a detected trigger example. The effectiveness of our defense is demonstrated experimentally for a wide variety of DNN architectures, datasets, and backdoor attack configurations.