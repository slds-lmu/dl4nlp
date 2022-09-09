---
title: "Chapter 7: Few-/Zero-Shot Learning & Prompting"
---
A concurring paradigm to the pretrain/finetune procedure, which most of the previously introduced architectures are subject to, is few- and zero-shot learning.
In this paradigm, a (large!) pre-trained architecture is _not_ fine-tuned to specific task, but prompted with a task description and a few labeled examples (or
none, in case of zero-shot) in order to predict the correct label for an instance simply due to its capabilites gained during pre-training.
