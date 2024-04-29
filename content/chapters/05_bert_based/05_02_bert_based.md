---
title: "Chapter 05.02: BERT-based architectures"
weight: 5002
---
For RoBERTa (Robustly optimized BERT approach), the basic idea is to improve upon the BERT architecture by training on more data with longer sequences, removing the next sentence prediction (NSP) objective, and utilizing dynamic masking during pretraining to enhance robustness and performance.
RoBERTa achieves this by pretraining on a larger corpus of text data with more training steps, larger batch sizes, and longer sequences compared to BERT. Additionally, it removes the NSP objective and employs dynamic masking, where masking patterns are dynamically sampled for each training instance, allowing the model to see different masked tokens across multiple epochs. This approach enhances the model's ability to capture contextual information and improves performance on various natural language understanding tasks.

As for ALBERT (A Lite BERT), the basic idea is to reduce the computational complexity of BERT while maintaining or improving performance by introducing parameter-sharing techniques and factorized embedding parameterization.
ALBERT achieves this by factorizing the embedding parameters and sharing them across layers, reducing the number of parameters and computational cost. These innovations enable ALBERT to achieve similar or better performance than BERT while being more memory-efficient and scalable, making it suitable for a wider range of applications and deployment scenarios.


<!--more-->

<!--
### Lecture video

{{< video id="TfrSKiOecWI" >}}
-->

### Lecture Slides

{{< pdfjs file="https://github.com/slds-lmu/lecture_dl4nlp/blob/main/slides/chapter05-bert-based/slides-52-bert-based.pdf" >}}

### Additional Resources

- [RoBERTa Blogpost](https://towardsdatascience.com/roberta-1ef07226c8d8)
- [ALBERT Blogpost](https://towardsdatascience.com/albert-22983090d062)


