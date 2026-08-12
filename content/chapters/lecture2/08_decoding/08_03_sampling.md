---
title: "Chapter 08.03: Stochastic Decoding & CS/CD"
weight: 8003
---
In this chapter you will learn about more methods beyond simple deterministic decoding strategies. We introduce sampling with temperature, where you add a temperature parameter into the softmax formula, top-k [1] and top-p [2] sampling, where you sample from a set of top tokens and finally contrastive search [3] and contrastive decoding [4].


<!--more-->

### Lecture Slides

{{< pdfjs file="https://github.com/slds-lmu/lecture_dl4nlp/blob/main/slides/chapter08-decoding/slides-83-sampling.pdf" >}}

### References

- [1] [Fan et al., 2018](https://arxiv.org/abs/1805.04833)
- [2] [Holtzman et al., 2019](https://arxiv.org/abs/1904.09751)
- [3] [Su et al., 2022](https://arxiv.org/abs/2210.14140)
- [4] [Li et al., 2023](https://arxiv.org/abs/2210.15097)