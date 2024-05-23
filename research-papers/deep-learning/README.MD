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
