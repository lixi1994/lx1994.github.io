---
title: "BIC-based Mixture Model Defense against Data Poisoning Attacks on Classifiers: A Comprehensive Study"
collection: publications
permalink: /publication/2024_BIC_defense
authors: <strong>Xi Li</strong>, David J. Miller, Zhen Xiang and George Kesidis
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
year: 2024
date: 2024-01-30  # Also make sure the date format is correct
venue: 'IEEE Transactions on Knowledge and Data Engineering (<strong>TKDE</strong>)'
paperurl: '/files/BIC_TKDE.pdf'
citation: 'Xi Li, David J. Miller, Zhen Xiang and George Kesidis. (2024). "BIC-based Mixture Model Defense against Data Poisoning Attacks on Classifiers: A Comprehensive Study." <i>TKDE</i>.'
header:
  teaser: "BIC.png"
---

Data Poisoning (DP) is an effective attack that causes trained classifiers to misclassify their inputs. DP attacks significantly degrade a classifier's accuracy by covertly injecting attack samples into the training set.
Broadly applicable to different classifier structures, without strong assumptions about the attacker, an unsupervised Bayesian Information Criterion (BIC)-based mixture model defense against "error generic" DP attacks 
is herein proposed that: 
1) addresses the most challenging embedded DP scenario wherein, if DP is present, the poisoned samples are an a priori unknown subset of the training set, and with no clean validation set available;
2) applies a mixture model both to well-fit potentially multi-modal class distributions and to capture poisoned samples within a small subset of the mixture components; 3) jointly identifies poisoned components and samples by minimizing the BIC cost defined over the whole training set, with the identified poisoned data removed prior to classifier training. 
Our experimental results, for various classifier structures and benchmark datasets, demonstrate the effectiveness of our defense under strong DP attacks, as well as its superiority over other DP defenses.
