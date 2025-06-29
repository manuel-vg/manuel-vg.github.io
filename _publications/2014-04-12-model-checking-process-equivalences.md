---
title: "Model-checking process equivalences"
collection: publications
category: manuscripts
permalink: /publication/2014-04-12-model-checking-process-equivalences
excerpt: 'This paper introduces a modal fixpoint logic framework that uniformly defines many process equivalences (like bisimulation and trace equivalence) and supports model checking in PTIME and PSPACE.'
date: 2014-04-12
venue: 'Theoretical Computer Science'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S0304397514006574'
citation: 'Martin Lange, Etienne Lozes, and Manuel Vargas Guzmán. (2014). &quot;Model-checking process equivalences.&quot; <i>Theoretical Computer Science</i>. 560(3). Pages 326-347'
---
Process equivalences are formal methods that relate programs and systems which, informally, behave in the same way. Since there is no unique notion of what it means for two dynamic systems to display the same behaviour there are a multitude of formal process equivalences, ranging from bisimulation to trace equivalence, categorised in the linear-time branching-time spectrum.
We present a logical framework based on an expressive modal fixpoint logic which is capable of defining many process equivalence relations: for each such equivalence there is a fixed formula which is satisfied by a pair of processes if and only if they are equivalent with respect to this relation.
We explain how to do model checking for this logic in EXPTIME. This allows model checking technology to be used for process equivalence checking. We introduce two fragments of the logic for which it is possible to do model-checking in PTIME and PSPACE respectively, and show that the formulas that define the process equivalences we consider are in one of these fragments. This yields a generic proof technique for establishing the complexities of these process equivalences.
Finally, we show how partial evaluation can be used to obtain decision procedures for process equivalences from the generic model checking scheme.
