---
title: "Chapter 5.5: Transformer-XL for long sequences"
weight: 5005
---
The Transfomer-XL is motivated by the problem of modeling long sequences with the Transformer architecture. While the computational complexity of the Vanilla Transformer
scales quadratically with the sequence length (and is this problematic), the authors here propose a segment recurrence mechanism to handle this problem efficiently.
Further the introduce _relative_ positional encodings (as opposed to absolute ones in the Vanilla Tranformer) to make the segment recurrence work in a meaningful way.

<!--more-->

<!--
### Lecture video
{{< video id="TfrSKiOecWI" >}}
-->

### Lecture Slides
{{< pdfjs file="https://github.com/slds-lmu/lecture_dl4nlp/blob/main/slides/chapter5-transformer/slides-55-trafo-xl.pdf" >}}

### References 

- [Dai et al. (2019)](https://aclanthology.org/P19-1285.pdf)
