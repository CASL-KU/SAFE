# SAFE: Selective Adapter Freezing for Memory Efficient Fine Tuning of Language Models
**[NAACL 2025] Not All Adapters Matter: Selective Adapter Freezing for Memory-Efficient Fine-Tuning of Language Models**


## Abstract

Transformer-based large-scale pre-trained models have achieved great success across various natural language processing tasks. Fine-tuning is the standard approach to adapt these models for downstream applications. Among the fine-tuning techniques, adapter-tuning offers a parameter-efficient method by introducing lightweight trainable modules while keeping the majority of pretrained parameters frozen. However, even with adapter-tuning, significant resource usage remains.

In this paper, we investigate the unequal contribution of each adapter to both task performance and resource consumption. Based on this insight, we propose **Selective Adapter FrEezing (SAFE)**, a method that gradually freezes less important adapters during the fine-tuning process to reduce unnecessary resource usage while maintaining or even improving performance.

Our experiments show that SAFE reduces:
- Memory usage by **42.85%**
- Computation amount by **34.59%**
- Training time by **11.82%**

While maintaining comparable or better task performance compared to the baseline. Additionally, SAFE induces a regularization effect that smooths the loss landscape, which helps the model generalize better by avoiding sharp minima.

## Code

The official code for the paper will be released soon. Stay tuned for updates!

## Installation

Instructions for setting up the environment and installing dependencies will be provided once the code is released.

## Citations

Please cite our work using the following Bibtex entry

```bibtex
@article{son2024not,
  title={Not All Adapters Matter: Selective Adapter Freezing for Memory-Efficient Fine-Tuning of Language Models},
  author={Son, Hyegang and Son, Yonglak and Kim, Changhoon and Kim, Young Geun},
  journal={arXiv preprint arXiv:2412.03587},
  year={2024}
}
```



We encourage researchers and practitioners to explore and apply **Selective Adapter FrEezing (SAFE)** to address challenges in memory-efficient fine-tuning, particularly in settings where resource constraints are critical. This approach offers a promising avenue for improving the performance and efficiency of language models in various real-world applications, especially in environments with limited computational resources.
