# SAFE: Selective Adapter Freezing for Memory Efficient Fine Tuning of Language Models
**[NAACL 2025] Not All Adapters Matter: Selective Adapter Freezing for Memory-Efficient Fine-Tuning of Language Models**


## Abstract

Transformer-based large-scale pre-trained models achieve great success. Fine-tuning is the standard practice for leveraging these models in downstream tasks. Among the fine-tuning methods, adapter-tuning provides a parameter-efficient fine-tuning by introducing lightweight trainable modules while keeping most pre-trained parameters frozen. However, existing adapter-tuning methods still impose substantial resource usage. Through our investigation, we show that each adapter unequally contributes to both task performance and resource usage. Motivated by this insight, we propose **Selective Adapter FrEezing (SAFE)**, which gradually freezes less important adapters early to reduce unnecessary resource usage while maintaining performance. In our experiments, SAFE reduces memory usage, computation amount, and training time by 42.85%, 34.59%, and 11.82%, respectively, while achieving comparable or better task performance compared to the baseline. We also demonstrate that SAFE induces regularization effect, thereby smoothing the loss landscape, which enables the model to generalize better by avoiding sharp minima.

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
