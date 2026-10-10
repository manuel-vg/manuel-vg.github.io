---
title: "Teaching Small Language Models to Learn Logic through Meta-Learning"
collection: publications
category: conferences
permalink: /publication/2026-03-24-teaching-small-language-models-to-learn-logic-through-meta-learning
excerpt: 'We study syllogistic reasoning in LLMs and show how meta-learning improves generalization.'
date: 2026-03-24
venue: 'European Chapter of the Association for Computational Linguistics (EACL)'
paperurl: 'https://aclanthology.org/2026.eacl-long.376.pdf'
citation: 'Leonardo Bertolazzi, Manuel Vargas Guzmán, Raffaella Bernardi, Maciej Malicki, and Jakub Szymanik (2026). &quot;Teaching Small Language Models to Learn Logic through Meta-Learning.&quot; <i>In Proceedings of the 19th Conference of the European Chapter of the Association for Computational Linguistics (Volume 1: Long Papers)</i>. Pages 8049–8080.'
---

Large language models (LLMs) are increasingly evaluated on reasoning tasks, yet their logical abilities remain contested. To address this, we study LLMs’ reasoning in a well-defined fragment of logic: syllogistic reasoning. We cast the problem as premise selection and construct controlled datasets to isolate logical competence. Beyond evaluation, an open challenge is enabling LLMs to acquire abstract inference patterns that generalize to novel structures. We propose to apply few-shot meta-learning to this domain, thereby encouraging models to extract rules across tasks rather than memorize patterns within tasks. Although meta-learning has been little explored in the context of logic learnability, our experiments show that it is effective: small models (1.5B–7B) fine-tuned with meta-learning demonstrate strong gains in generalization, with especially pronounced benefits in low-data regimes. These meta-learned models outperform GPT-4o and o3-mini on our syllogistic reasoning task.
