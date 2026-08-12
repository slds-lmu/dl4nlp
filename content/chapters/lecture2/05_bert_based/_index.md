---
title: "Chapter 5: Post-BERT Era"
---
Creating BERT-based models with modifications to pretraining involves adjusting the pretraining objectives or architecture to suit specific tasks or domains.This process typically begins by designing custom pre-training objectives or modifying existing ones to capture domain-specific characteristics or improve model performance on targeted tasks. These modified pre-training objectives can include variations of masked language modeling (MLM), next sentence prediction (NSP), or other self-supervised learning tasks tailored to the needs of the target domain. After pretraining, the model is fine-tuned on downstream tasks using task-specific data and objectives, enabling it to adapt its learned representations to the specific requirements of the tasks. In this chapter you will learn about three different cases where the existing BERT model has been modified, namely RoBERTa [1], ALBERT [2] and DistillBERT [3].

<!--more-->

### References 

- [1] [Liu et al., 2019](https://arxiv.org/abs/1907.11692)
- [2] [Lan et al., 2020](https://arxiv.org/abs/1909.11942)
- [3] [Sanh et al., 2020](https://arxiv.org/abs/1910.01108)

