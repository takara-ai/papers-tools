# Deep Learning Papers

This directory contains curated research papers related to deep learning.

## Papers

### Scaling Monosemanticity

- **Authors**: Adly Templeton*, Tom Conerly*, Jonathan Marcus, Jack Lindsey, Trenton Bricken, Brian Chen, Adam Pearce, Craig Citro, Emmanuel Ameisen, Andy Jones, Hoagy Cunningham, Nicholas L Turner, Callum McDougall, Monte MacDiarmid, Alex Tamkin, Esin Durmus, Tristan Hume, Francesco Mosconi, C. Daniel Freeman, Theodore R. Sumers, Edward Rees, Joshua Batson, Adam Jermyn, Shan Carter, Chris Olah, Tom Henighan
- **Affiliation**: Anthropic
- **Published**: May 21, 2024
- **Link**: [Scaling Monosemanticity](https://transformer-circuits.pub/2024/scaling-monosemanticity/index.html)
- **Summary**: This paper explores the scalability of sparse autoencoders to extract interpretable features from large transformer models, like Claude 3 Sonnet. The study finds highly abstract features relevant to AI safety, including security vulnerabilities, bias, and deception. It demonstrates the potential of these features to influence model behavior and emphasizes the need for further research to understand their implications.

### Adversarial Diffusion Distillation

- **Authors**: Axel Sauer, Dominik Lorenz, Andreas Blattmann, Robin Rombach
- **Affiliation**: Stability AI
- **Published**: May 21, 2024
- **Link**: [Adversarial Diffusion Distillation](https://static1.squarespace.com/static/6213c340453c3f502425776e/t/65663480a92fba51d0e1023f/1701197769659/adversarial_diffusion_distillation.pdf)
- **Summary**: This paper introduces Adversarial Diffusion Distillation (ADD), a training approach that efficiently samples large-scale foundational image diffusion models in 1–4 steps while maintaining high image quality. By combining score distillation with an adversarial loss, ADD outperforms existing few-step methods and reaches the performance of state-of-the-art diffusion models in only four steps. ADD enables real-time, high-fidelity image synthesis with large models.

### Attention Is All You Need

- **Authors**: Ashish Vaswani*, Noam Shazeer*, Niki Parmar*, Jakob Uszkoreit*, Llion Jones*, Aidan N. Gomez†, Łukasz Kaiser*, Illia Polosukhin‡
- **Affiliations**: Google Brain, Google Research, University of Toronto
- **Published**: June 12, 2017 (31st Conference on Neural Information Processing Systems, NIPS 2017)
- **Link**: [Attention Is All You Need](https://arxiv.org/abs/1706.03762)
- **Summary**: This paper introduces the Transformer model, a novel architecture based solely on attention mechanisms, eschewing recurrence and convolutions entirely. The Transformer demonstrates superior performance in machine translation tasks, achieving state-of-the-art results with significantly improved parallelization and reduced training times. The model achieves 28.4 BLEU on the WMT 2014 English-to-German translation task and 41.8 BLEU on the WMT 2014 English-to-French translation task, setting new benchmarks in translation quality. The Transformer also generalizes well to other tasks, such as English constituency parsing.

### Textbooks Are All You Need

- **Authors**: Suriya Gunasekar, Yi Zhang, Jyoti Aneja, Caio César Teodoro Mendes, Allie Del Giorno, Sivakanth Gopi, Mojan Javaheripi, Piero Kauffmann, Gustavo de Rosa, Olli Saarikivi, Adil Salim, Shital Shah, Harkirat Singh Behl, Xin Wang, Sébastien Bubeck, Ronen Eldan, Adam Tauman Kalai, Yin Tat Lee, Yuanzhi Li
- **Affiliation**: Microsoft Research
- **Published**: October 2, 2023
- **Link**: [Textbooks Are All You Need](https://arxiv.org/abs/2306.11644)
- **Summary**: This paper introduces phi-1, a Transformer-based large language model for code with 1.3B parameters, significantly smaller than competing models. Trained on "textbook quality" data from the web and synthetically generated textbooks, phi-1 achieves impressive results with pass@1 accuracy of 50.6% on HumanEval and 55.5% on MBPP. The study highlights the importance of high-quality data in achieving state-of-the-art results with reduced model size and training compute, demonstrating that high-quality data can break existing scaling laws in deep learning.

### MoRA: High-Rank Updating for Parameter-Efficient Fine-Tuning

- **Authors**: Ting Jiang, Shaohan Huang, Shengyue Luo, Zihan Zhang, Haizhen Huang, Furu Wei, Weiwei Deng, Feng Sun, Qi Zhang, Deqing Wang, Fuzhen Zhuang
- **Affiliations**: Beihang University, Microsoft Corporation
- **Published**: May 20, 2024
- **Link**: [MoRA: High-Rank Updating for Parameter-Efficient Fine-Tuning](https://arxiv.org/abs/2405.12130)
- **Summary**: This paper presents MoRA, a method that employs a square matrix for high-rank updating in parameter-efficient fine-tuning (PEFT) of large language models (LLMs), contrasting with the low-rank adaptation approach of LoRA. MoRA maintains the same number of trainable parameters while achieving superior performance on memory-intensive tasks and comparable results on other tasks. It introduces non-parameter operators to adjust input and output dimensions, enabling the integration of high-rank updates back into LLMs. The effectiveness of MoRA is demonstrated through comprehensive evaluations across various tasks including instruction tuning, mathematical reasoning, continual pretraining, and pretraining from scratch.
