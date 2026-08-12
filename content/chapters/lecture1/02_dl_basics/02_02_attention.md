---
title: "Chapter 02.02 Attention"
weight: 2002
---

This chapter will give you a first introduction into the concept of Attention, as introduced in [1]. Attention mechanisms allow neural networks to focus on specific parts of the input sequence, assigning varying degrees of importance to different elements, enhancing performance especially in tasks where long-range dependencies are crucial, overcoming limitations of LSTMs and vanilla bidirectional RNNs which struggle with retaining information across long sequences or capturing complex relationships between distant elements. This is achieved by dynamically weighting the importance of different parts of the input sequence during computation, enabling the model to attend to relevant information and effectively process inputs of varying lengths.

<!--more-->

### Lecture slides

{{< pdfjs file="https://github.com/slds-lmu/lecture_dl4nlp/blob/main/slides/chapter02-deeplearningbasics/slides-22-attention.pdf" >}}

### References 

- [1] [Bahdanau et al., 2014](https://arxiv.org/abs/1409.0473)