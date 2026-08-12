---
title: "Chapter 05.03: Model distillation"
weight: 5003
---
For model distillation, the basic idea is to transfer knowledge from a large, computationally expensive model (e.g., BERT) to a smaller, more efficient model (e.g., DistilBERT) by distilling the large model's knowledge into the smaller one through a process called distillation.
DistilBERT, as an example, achieves this by first pretraining a large BERT model on a large corpus of text data using standard pre-training objectives. Then, the knowledge learned by the large model is transferred to a smaller, distilled model, such as DistilBERT, by training the smaller model to mimic the behavior of the larger model. This is typically done by minimizing the discrepancy between the probability distributions of the predictions made by the large model and the distilled model on the same input data.
During this process, unnecessary parameters and redundant information are discarded, resulting in a smaller and more efficient model while retaining much of the performance of the larger model. This allows for faster inference and deployment in resource-constrained environments without sacrificing much in terms of performance. DistilBERT, specifically, achieves a significant reduction in model size and computational cost compared to BERT while maintaining competitive performance across various NLP tasks.


<!--more-->

<!--
### Lecture video

{{< video id="TfrSKiOecWI" >}}
-->

### Lecture Slides

{{< pdfjs file="https://github.com/slds-lmu/lecture_dl4nlp/blob/main/slides/chapter05-bert-based/slides-53-distilbert.pdf" >}}

### Additional Resources 

- [Nice video explaining Model Distillation](https://www.youtube.com/watch?v=rNOuDKWtrAE)
