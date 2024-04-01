---
title: "Temporal-Distributed Backdoor Attack Against Video Based Action Recognition"
collection: publications
permalink: /publication/2024_video_backdoor
authors: <strong>Xi Li</strong>, Songhe Wang, Ruiquan Huang, Mahanth Gowda, and George Kesidis
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
year: 2024
date: 2024-02-21  # Also make sure the date format is correct
venue: 'The 38th Annual AAAI Conference on Artificial Intelligence (<strong>AAAI</strong>)'
paperurl: '/files/2024_AAAI.pdf'
posterlink: '/files/AAAI24_poster.pdf'
codelink: 'https://github.com/lixi1994/TDBA-VAR'
citation: 'Xi Li, Songhe Wang, Ruiquan Huang, Mahanth Gowda, George Kesidis. (2024). "Temporal-Distributed Backdoor Attack Against Video Based Action Recognition." <i>AAAI</i>.'
header:
  teaser: "2024_AAAI.png"
---

Deep neural networks (DNNs) have achieved tremendous success in various applications including video action recognition, yet remain vulnerable to backdoor attacks (Trojans). 
The backdoor-compromised model will mis-classify to the target class chosen by the attacker when a test instance (from a non-target class) is embedded with a specific trigger, while maintaining high accuracy on attack-free instances. 
Although there are extensive studies on backdoor attacks against image data, the susceptibility of video-based systems under backdoor attacks remains largely unexplored.
Current studies are direct extensions of approaches proposed for image data, e.g., the triggers are independently embedded within the frames, which tend to be detectable by existing defenses. In this paper, we introduce a simple yet effective backdoor attack against video data. Our proposed attack, adding perturbations in a transformed domain, plants an imperceptible, temporally distributed trigger across the video frames, and is shown to be resilient to existing defensive strategies. 
The effectiveness of the proposed attack is demonstrated by extensive experiments with various well-known models on two video recognition benchmarks, UCF101 and HMDB51, and a sign language recognition benchmark, Greek Sign Language (GSL) dataset. 
We delve into the impact of several influential factors on our proposed attack and identify an intriguing effect termed "collateral damage" through extensive studies.
