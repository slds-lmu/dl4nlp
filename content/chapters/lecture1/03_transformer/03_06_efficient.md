---
title: "Chapter 03.06: Efficient Transformers"
weight: 3006
---
Efficient Transformers are designed to mitigate the computational and memory requirements of standard transformer architectures, particularly when dealing with large-scale datasets or resource-constrained environments. They aim to address issues such as scalability and efficiency in training and inference. One approach used in efficient transformers is replacing the standard self-attention mechanism with more lightweight attention mechanisms, which reduce the computational complexity of attending to long sequences by approximating the attention mechanism with lower-rank matrices or restricting attention to local or sparse regions of the sequence. These approaches enable transformers to be more practical for real-world applications where computational resources are limited.

<!--more-->

<!--
### Lecture video
{{< video id="TfrSKiOecWI" >}}
-->

### Lecture Slides
{{< pdfjs file="https://github.com/slds-lmu/lecture_dl4nlp/blob/main/slides/chapter03-transformer/slides-36-efficient.pdf" >}}

### Additional Resources

[Blogpost about Flash Attention](https://huggingface.co/docs/text-generation-inference/conceptual/flash_attention)

