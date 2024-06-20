---
title: "Chapter 03.04: Transformer Parameter Count"
weight: 3004
---
This chapter deals with the number of parameters of the transformer. The parameter count of a transformer model refers to the total number of learnable parameters present in its architecture, which are distributed across various components of the model. 
These components typically include:

1. **Embedding Layers**: Parameters associated with the input and output embeddings for tokens, which encode their semantic meanings.
2. **Encoder Layers**: Parameters within each encoder layer, including those associated with self-attention mechanisms, position-wise feedforward networks, and layer normalization.
3. **Decoder Layers**: Parameters within each decoder layer, including self-attention mechanisms, cross-attention mechanisms, position-wise feedforward networks, and layer normalization.
4. **Positional Encodings**: Parameters used to encode positional information in the input sequences.

The total parameter count of a transformer model is the sum of parameters from all these components, with variations depending on the specific architecture and hyperparameters chosen for the model.


<!--more-->

<!--
### Lecture video
{{< video id="TfrSKiOecWI" >}}
-->

### Lecture Slides
{{< pdfjs file="https://github.com/slds-lmu/lecture_dl4nlp/blob/chapter11/slides/chapter03-transformer/slides-34-trafo-params.pdf" >}}

### Additional Resources

- [Blog about the Transformer Parameter Count](https://towardsdatascience.com/how-to-estimate-the-number-of-parameters-in-transformer-models-ca0f57d8dff0)

