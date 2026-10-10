---
title: "Testing the limits of logical reasoning in neural and hybrid models"
collection: talks
type: "Talk"
permalink: /talks/2026-01-08-Testing the limits of logical reasoning in neural and hybrid models
venue: "Compositionality and Reasoning in AI and Cognitive Science"
date: 2026-01-08
location: "Warsaw, Poland"
---

[More information here](https://manuel-vg.github.io/compositionality-workshop-2026/)

**Abstract.** We study neural and hybrid models of reasoning, analyzing the extent to which neural networks can generalize logical reasoning patterns to assist in the construction of symbolic proofs. To this end, we introduce a unified framework, inspired by compositional tests, for evaluating generalization in logical reasoning. We use syllogistic logic to generate controlled synthetic data for our experiments. First, we train multiple neural architectures under different experimental setups to predict a minimal set of premises required to prove a given hypothesis. Our results show that, although models capture basic logical properties, their ability to generalize remains limited. In particular, while models can generalize from simple to longer inference chains, they struggle to transfer rules learned from complex to simpler cases. We then integrate neural predictors with a symbolic syllogistic prover to assist in proof construction, including proof-by-contradiction steps. Despite the aforementioned limitations, the resulting hybrid models offer favorable time-complexity trade-offs through neural guidance of symbolic search. We empirically demonstrate that differences in neural component size and generalization do not affect the system’s overall robustness. These findings motivate further investigation of neuro-symbolic approaches for proof construction, as such models integrate the strengths of both paradigms to yield interpretable, formally sound reasoning.
