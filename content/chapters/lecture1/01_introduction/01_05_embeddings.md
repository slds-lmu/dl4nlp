---
title: "Chapter 01.05: Word Embeddings"
weight: 1005

---
Embeddings allow us to represent tokens with a vector representation, enabling computers to efficiently understand the meaning and context of different words. In this chapter we will first explain the general concept of embeddings and then introduce two popular approaches, namely Word2Vec [1] and FastText [2]. Word2vec is a neural network model that learns distributed representations of words in a continuous vector space based on their contextual usage in a corpus of text. Word2vec achieves this by training on a large dataset to predict the surrounding words given a target word, embedding each word as a dense vector where similar words are closer together in the vector space. FastText is an extension of Word2vec that represents words as bags of character n-grams, enabling it to capture morphological information alongside semantics. It accomplishes this by breaking down each word into character n-grams, creating embeddings for these subword units, and then summing or averaging these embeddings to obtain the representation for the whole word.   

<!--more-->

### Lecture slides

{{< pdfjs file="https://github.com/slds-lmu/lecture_dl4nlp/blob/main/slides/chapter01-basics/slides-15-embeddings.pdf" >}}

### References 

- [1] [Mikolov et al., 2013](https://arxiv.org/abs/1301.3781)
- [2] [Bojanowski et al., 2016](https://arxiv.org/abs/1607.04606)

### Additional Resources 

- [Word2vec Blogpost](https://israelg99.github.io/2017-03-23-Word2Vec-Explained/) 