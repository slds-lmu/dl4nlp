---
title: "Chapter 4.1: ARLMs vs. MLM"
weight: 4010
---
ARLM (Auto-Regressive Language Modeling) and MLM (Masked Language Modeling) are both self-supervised learning objectives used in pretraining transformer-based language models like BERT.  ARLM involves predicting the next word in a sequence given the previous context, while MLM involves masking some of the input tokens and predicting them based on the surrounding context. Both methods leverage self-supervision, where the model learns from the data itself without requiring explicit labels, enabling it to capture meaningful representations of language. 

<!--more-->

<!--
### Lecture video

{{< video id="TfrSKiOecWI" >}}
-->

### Lecture Slides
{{< pdfjs file="https://github.com/slds-lmu/lecture_dl4nlp/blob/main/slides/chapter04-bert/slides-41-arlm-mlm.pdf" >}}
