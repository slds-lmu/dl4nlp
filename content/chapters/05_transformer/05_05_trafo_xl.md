---
title: "Chapter 5.5: Transformer-XL for long sequences"
weight: 5005
---
The Transfomer-XL is motivated by the problem of modeling long sequences with the Transformer architecture. While the computational complexity of the Vanilla Transformer
scales quadratically with the sequence length (and is this problematic), the authors here propose a segment recurrence mechanism to handle this problem efficiently.
Further the introduce _relative_ positional encodings (as opposed to absolute ones in the Vanilla Tranformer) to make the segment recurrence work in a meaningful way.

<!--more-->

### Concept 
6 slides, 10 minutes

<!--
### Lecture video
{{< video id="TfrSKiOecWI" >}}
### Lecture Slides
{{< pdfjs file="https://github.com/slds-lmu/lecture_i2ml/blob/master/slides-pdf/slides-basics-whatisml.pdf" >}}
-->

### References 

- [Dai et al. (2019)](https://aclanthology.org/P19-1285.pdf)
