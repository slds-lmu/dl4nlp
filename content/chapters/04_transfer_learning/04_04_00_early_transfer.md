---
title: "Chapter 4.4: Early Transfer Learning architectures"
weight: 4040
---
Before the use of the Transformer architecture ([cf. Chapter 5](https://slds-lmu.github.io/dl4nlp/chapters/05_transformer/)) for Transfer Learning, two milestone architectures were published.

<!--more-->

Their importance stems from two pioneering paradigms they introduced: ELMo was the first model to learn word embeddings which embraces contextuality in a bidirectional way, meaning that the vector representation of a word depends on both the context on its left as well as the context on its right side.
The other architecture, ULMFiT, is not only about creating embeddings but (pre-)training a _whole architecture_ which can be adapted to data from the target task or domain.
