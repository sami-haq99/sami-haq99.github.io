---
title: "Simultaneous Translation"
collection: research
permalink: /research/future_info_for_sim_mt
excerpt: "This project aims to improve the simultaneous translation system *wait-k* by using future information. More specifically, we trained *wait-k* system with larger *k'* (more future information and larger latency) during training. To adaptively select *k'*, we jointly train a controller via REINFORCE algorithm. Our method improved 1.0 - 3.0 BLEU (under similar latency) on large WMT dataset and small IWSLT datasets. The paper is currently under review, and the arxiv link is [https://arxiv.org/abs/2007.05290](https://arxiv.org/abs/2007.05290)."
start_date: Dec. 2019
date: Jul. 2020
---

This project aims to improve the simultaneous translation system *wait-k* by using future information. More specifically, we trained *wait-k* system with larger *k'* (more future information and larger latency) during training. To adaptively select *k'*, we jointly train a controller via REINFORCE algorithm. Our method improved 1.0 - 3.0 BLEU (under similar latency) on large WMT dataset and small IWSLT datasets. The paper is currently under review, and the arxiv link is [https://arxiv.org/abs/2007.05290](https://arxiv.org/abs/2007.05290).

**Paper abstract**:

Simultaneous neural machine translation (briefly, NMT) has attracted much attention recently. In contrast to standard NMT, where the NMT system can utilize the full input sentence, simultaneous NMT is formulated as a prefix-to-prefix problem, where the system can only utilize the prefix of the input sentence and more uncertainty is introduced to decoding. Wait-k [10] is a simple yet effective strategy for simultaneous NMT, where the decoder generates the output sequence k words behind the input words. We observed that training simultaneous NMT systems with future information (i.e., trained with a larger k) generally outperforms the standard ones (i.e., trained with the given k). Based on this observation, we propose a framework that automatically learns how much future information to use in training for simultaneous NMT. We first build a series of tasks where each one is associated with a different k, and then learn a model on these tasks guided by a controller. The controller is jointly trained with the translation model through bi-level optimization. We conduct experiments on four datasets to demonstrate the effectiveness of our method.