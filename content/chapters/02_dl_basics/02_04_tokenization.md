---
title: "Chapter 02.04 Revisiting words: Tokenization"
weight: 2004
---
This chapter is about Tokenization, which is the process of breaking down a sequence of text into smaller, meaningful units, such as words or subwords, to facilitate natural language processing tasks. Various tokenization methods exist, including Byte Pair Encoding (BPE) [1] or WordPiece [2], each with its own approach to dividing text into tokens. BPE and WordPiece are subword tokenization techniques that iteratively merge frequent character sequences to form larger units, effectively capturing both common words and rare morphological variations.

<!--more-->

### Lecture slides

{{< pdfjs file="https://github.com/slds-lmu/lecture_dl4nlp/blob/main/slides/chapter02-deeplearningbasics/slides-24-tokenization.pdf" >}}

### References

- [1] [Sennrich et al., 2015](https://arxiv.org/abs/1508.07909)
- [2] [Wu et al., 2016](https://arxiv.org/pdf/1609.08144v2.pdf)

### Additional Resources

- [Huggingface WordPiece Tutorial](https://huggingface.co/learn/nlp-course/chapter6/6)