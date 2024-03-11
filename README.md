# Task-vectors-for-LLMs

![task_vectors](https://github.com/FedericoAlvetreti/Task-vectors-for-LLMs/assets/115395996/bdca07d6-ac25-41a4-9ac9-3d520d8fba8c)


Proposed in ["Editing Models with Task Arithmetic"](https://arxiv.org/abs/2212.04089), task arithmetic is a new paradigm for adapting neural networks to new tasks.

This paradigm is based on task vectors, defined as a direction in the weight
space of a pre-trained model towards a space region in which results on a
task are improved.
Such vectors, once obtained, can be added or subtracted, leading to different results.

In this project we use the [Hugging Face](https://huggingface.co/) pre-trained BERT model to train two errors detection models:
 - one focused on spelling errors;
 - one focused on logical errors.


Lastly we use tasks vectors in order to generate a more general model able to detect both.
