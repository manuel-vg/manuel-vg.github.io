---
title: "Hybrid Models of Natural Reasoning"
collection: talks
type: "Talk"
permalink: /talks/2025-02-10-hybrid-models-of-natural-reasoning
venue: "33rd EACSL Annual Conference on Computer Science Logic, Amsterdam Science Park"
date: 2025-02-10
location: "Amsterdam, the Netherlands"
---

[More information here](https://sites.google.com/view/lealog25)

**Abstract.** Within the Artificial Intelligence field, the ability to perform reasoning can be modelled using symbolic and connectionist approaches. Both types of models achieve a conclusion in a different fashion, while the former applies formal logic and the transformation of premises using inference rules, the latter uses neural networks. We combine these two techniques within a framework of a formally well-defined subclass of natural language to study abstract models of reasoning. We implement a symbolic prover and train neural models for one of the simplest subclasses of language, the syllogistic fragment. Our hybrid model constructs inferences using the symbolic model assisted by the connectionist one in the following tasks: for a given knowledge base KB (a set of premises) and a hypothesis H, the neural network provides the necessary premises (a subset of KB) to prove H and, if needed, it also predicts a formula to prove H by contradiction. To build a connectionist component, we use synthetic data and fine-tuning approaches on pre-trained Large Language Models. Our experiments show that a successful collaboration between symbolic and connectionist models lead to a significant decrease in the number of computations that a “naive” symbolic prover would need to find inferences.
