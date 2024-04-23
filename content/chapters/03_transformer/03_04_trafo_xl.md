---
title: "Chapter 03.04: Long Sequences: Transformer-XL"
weight: 3004
---
This chapter is about the Transformer-XL [1] and how it deals with the issue of long sequences. Transformer-XL is an extension of the original Transformer architecture designed to address the limitations of long-range dependency modeling in sequence-to-sequence tasks. It aims to solve the problem of capturing and retaining information over long sequences by introducing a segment-level recurrence mechanism, enabling the model to process sequences of arbitrary length without being constrained by fixed-length contexts or running into computational limitations. Additionally, Transformer-XL incorporates relative positional embeddings to better capture positional information across segments of varying lengths. 

<!--more-->

<!--
### Lecture video
{{< video id="TfrSKiOecWI" >}}
-->

### Lecture Slides
{{< pdfjs file="https://github.com/slds-lmu/lecture_dl4nlp/blob/main/slides/chapter03-transformer/slides-34-trafo-xl.pdf" >}}

### References 

- [1] [Dai et al., 2019](https://arxiv.org/abs/1901.02860)
