---
title: "Chapter 4.4: Pre-training & Fine-Tuning"
weight: 4040
---
In the pre-training phase of BERT, the model is trained on large text corpora using self-supervised learning objectives such as masked language modeling (MLM) and next sentence prediction (NSP). During MLM a certain percentage of input tokens are randomly masked and the model is trained to predict the masked tokens based on the surrounding context. In NSP the model learns to predict whether two sentences in a pair are consecutive or not. This pre-training phase allows BERT to learn rich contextual representations of words and sentences.
In the fine-tuning phase BERT is adapted to specific downstream tasks by adding task-specific output layers and fine-tuning the pretrained parameters on task-specific labeled data. During fine-tuning only a small portion of the parameters are updated, while the majority of the pretrained parameters remain fixed. This process allows BERT to leverage the general linguistic knowledge learned during pretraining and adapt it to the specific requirements of the downstream tasks, resulting in improved performance on tasks such as text classification, named entity recognition, and question answering.


<!--more-->

### Lecture Slides

{{< pdfjs file="https://github.com/slds-lmu/lecture_dl4nlp/blob/main/slides/chapter04-bert/slides-44-pretrain-finetune.pdf" >}}
