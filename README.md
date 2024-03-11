# Task-vectors-for-LLMs

![task vectors](https://github.com/gabriele-pelliccioni/Task-Vectors-Fine-Tuning/assets/115414129/c8b654a6-e28b-4b3b-8be9-a87a08da686e)


Proposed in ["Editing Models with Task Arithmetic"](https://arxiv.org/abs/2212.04089), task arithmetic is a new paradigm for adapting neural networks to new tasks.

This paradigm is based on task vectors, defined as a direction in the weight
space of a pre-trained model towards a space region in which results on a
task are improved.
Such vectors, once obtained, can be added or subtracted, leading to different results.

In this project we use the [Hugging Face](https://huggingface.co/) pre-trained BERT model to train two errors detection models:
 - one focused on spelling errors;
 - one focused on logical errors.


Lastly we use tasks vectors in order to generate a more general model able to detect both.
