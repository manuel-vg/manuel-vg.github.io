---
title: "Model-Checking Process Equivalences"
collection: publications
category: conferences
permalink: /publication/2012-09-06-model-checking-process-equivalences
excerpt: 'The paper introduces a modal fixpoint logic framework that uniformly defines many process equivalences (like bisimulation and trace equivalence). It enables symbolic model checking for a large fragment of the logic, and uses partial evaluation to derive decision procedures for verifying process equivalence.'
date: 2012-09-06
venue: 'Games, Automata, Logic and Formal Verification (GandALF)'
paperurl: 'https://arxiv.org/pdf/1210.2451v1'
citation: 'Martin Lange, Etienne Lozes, and Manuel Vargas Guzmán. (2012). &quot;Model-Checking Process Equivalences.&quot; <i>Games, Automata, Logic and Formal Verification (GandALF)</i>. Pages 43-56.'
---

Process equivalences are formal methods that relate programs and system which, informally, behave in the same way. Since there is no unique notion of what it means for two dynamic systems to display the same behaviour there are a multitude of formal process equivalences, ranging from bisimulation to trace equivalence, categorised in the linear-time branching-time spectrum.
We present a logical framework based on an expressive modal fixpoint logic which is capable of defining many process equivalence relations: for each such equivalence there is a fixed formula which is satisfied by a pair of processes if and only if they are equivalent with respect to this relation. We explain how to do model checking, even symbolically, for a significant fragment of this logic that captures many process equivalences. This allows model checking technology to be used for process equivalence checking. We show how partial evaluation can be used to obtain decision procedures for process equivalences from the generic model checking scheme.
