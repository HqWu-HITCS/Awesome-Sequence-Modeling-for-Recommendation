<h1 align="center">
Awesome-Sequence-Modeling-for-Recommendation
</h1>
<p align="center">
<font face="黑体" color=orange size=3"> An Awesome Collection for Sequential Recommendation and Sequence Modeling in Recommend System</font>
</p>

<p align="center">
  <a href="https://github.com/HqWu-HITCS/Awesome-Sequence-Modeling-for-Recommendation/stargazers"> <img src="https://img.shields.io/github/stars/HqWu-HITCS/Awesome-Sequence-Modeling-for-Recommendation.svg?style=popout-square" alt="GitHub stars"></a>
  <a href="https://github.com/HqWu-HITCS/Awesome-Sequence-Modeling-for-Recommendation/issues"> <img src="https://img.shields.io/github/issues/HqWu-HITCS/Awesome-Sequence-Modeling-for-Recommendation.svg?style=popout-square" alt="GitHub issues"></a>
  <a href="https://github.com/HqWu-HITCS/Awesome-Sequence-Modeling-for-Recommendation/forks"> <img src="https://img.shields.io/github/forks/HqWu-HITCS/Awesome-Sequence-Modeling-for-Recommendation.svg?style=popout-square" alt="GitHub forks"></a>
</p>

This repository is to collect the resource of sequential recommendation and sequence modeling in recommend System.

We strongly encourage the researchers that want to promote their fantastic work to this community to make pull request to update their paper's information!

Keyword: Recommend System, sequential recommend, sequence modeling

Welcome to open an issue or make a pull request!

- [Tutorial ](#tutorial)
- [Survey](#survey)
- [Richer Sequence](#richer-sequence)
  - [Side/Session information modeling](#sidesession-information-modeling)
  - [Text information modeling](#text-information-modeling)
  - [Multi-Behavior modeling](#multi-behavior-modeling)
  - [Long Sequence Modeling](#long-sequence-modeling)
- [Model Structure](#model-structure)
  - [Attention](#attention)
  - [MLP](#mlp)
  - [GNN](#gnn)
  - [VAE](#vae)
- [Model Training](#model-training)
  - [Learning Paradigm](#learning-paradigm)
  - [Negative sampling](#negative-sampling)
  - [Data Augmentation](#data-augmentation)
- [Tool](#tool)
- [Related Repository](#related-repository)


# Tutorial 

-  [[SIGIR22l] Sequential/Session-based Recommendations: Challenges, Approaches, Applications and Opportunities ](https://neurec22.github.io/SRS&SBRS/)


# Survey

- [[IJCAI19] Sequential Recommender Systems: Challenges, Progress and Prospects](https://arxiv.org/abs/2001.04830)


# Richer Sequence

## Side/Session information modeling

- [[SIGIR22] Decoupled Side Information Fusion for Sequential Recommendation](https://arxiv.org/pdf/2204.11046.pdf)

- [[SIGIR22] Exploiting Session Information in BERT-based Session-aware Sequential Recommendation](https://arxiv.org/pdf/2204.10851.pdf)

- [[WWW22] Sequential Modeling with Multiple Attributes for Watchlist Recommendation in E-Commerce](https://arxiv.org/pdf/2110.11072.pdf)

- [[AAAI21] Non-invasive Self-attention for Side Information Fusion in Sequential Recommendation](https://arxiv.org/abs/2103.03578)

## Text information modeling

- [[KDD23] Text Is All You Need: Learning Language Representations for Sequential Recommendation](https://arxiv.org/pdf/2305.13731.pdf)

- [[KDD22] Towards Universal Sequence Representation Learning for Recommender Systems](https://arxiv.org/pdf/2206.05941.pdf)

## Multi-Behavior modeling

- [[CIKM22] Dual-Task Learning for Multi-Behavior Sequential Recommendation](https://dl.acm.org/doi/10.1145/3511808.3557298)

- [[SIGIR22] Multi-Behavior Sequential Transformer Recommender](https://dl.acm.org/doi/abs/10.1145/3477495.3532023)

- [[IJCAI22] Self-supervised Graph Neural Networks for Multi-behavior Recommendation](http://shichuan.org/doc/134.pdf)

- [[TKDE22] Multi-Behavior Sequential Recommendation with Temporal Graph Transformer](https://arxiv.org/pdf/2206.02687.pdf)

## Long Sequence Modeling

- [[CIKM22] Sampling Is All You Need on Modeling Long-Term User Behaviors for CTR Prediction](https://arxiv.org/abs/2205.10249)

- [[Arxiv21] End-to-End User Behavior Retrieval in Click-Through Rate Prediction Model](https://arxiv.org/pdf/2108.04468.pdf)

- [[CIKM20] Search-based User Interest Modeling with Lifelong Sequential Behavior Data for Click-Through Rate Prediction](https://dl.acm.org/doi/abs/10.1145/3340531.3412744)

- [[KDD19] Practice on Long Sequential User Behavior Modeling for Click-Through Rate Prediction](https://dl.acm.org/doi/10.1145/3292500.3330666)


# Model Structure

## Attention

- [[KDD23] Adaptive Disentangled Transformer for Sequential Recommendation](http://mn.cs.tsinghua.edu.cn/xinwang/PDF/papers/2023_Adaptive%20Disentangled%20Transformer%20for%20Sequential%20Recommendation.pdf)

- [[CIKM22] Disentangling Past-Future Modeling in Sequential Recommendation via Dual Networks](https://arxiv.org/abs/2210.14577)

- [[ICDE22] One Person, One Model—Learning Compound Router for Sequential Recommendation](https://arxiv.org/pdf/2211.02824.pdf)

- [[CIKM21] Modeling Sequences as Distributions with Uncertainty for Sequential Recommendation](https://dl.acm.org/doi/pdf/10.1145/3459637.3482145)

- [[WWW22] Sequential Recommendation via Stochastic Self-Attention](https://arxiv.53yu.com/pdf/2201.06035.pdf)

- [[CIKM19] BERT4Rec: Sequential Recommendation with Bidirectional Encoder Representations from Transformer](https://arxiv.org/abs/1904.06690)

## MLP

- [[WWW22] AutoMLP: Automated MLP for Sequential Recommendations](https://arxiv.org/pdf/2303.06337.pdf)

- [[IjCAI22] MLP4Rec: A Pure MLP Architecture for Sequential Recommendations](https://arxiv.org/pdf/2204.11510.pdf)

- [[WWW22] Filter-enhanced MLP is All You Need for Sequential Recommendation](https://arxiv.org/pdf/2202.13556.pdf)


## GNN

- [[SIGIR23] Graph Masked Autoencoder for Sequential Recommendation](https://arxiv.org/pdf/2305.04619.pdf)

- [[IJCAI22] Enhancing Sequential Recommendation with Graph Contrastive Learning](https://arxiv.org/pdf/2205.14837.pdf)

- [[ICDE21] Edge-Enhanced Global Disentangled Graph Neural Network for Sequential Recommendation](https://arxiv.org/pdf/2111.10539.pdf)

- [[SIGIR21] Sequential Recommendation with Graph Neural Networks](https://arxiv.org/pdf/2106.14226.pdf)

## VAE

- [[CIKM22] ContrastVAE: Contrastive Variational AutoEncoder for Sequential Recommendation](https://arxiv.org/pdf/2103.10693.pdf)

- [[WWW21] Adversarial and Contrastive Variational Autoencoder for Sequential Recommendation](https://arxiv.org/pdf/2103.10693.pdf)

# Model Training

## Learning Paradigm

- [[RecSys2023] Equivariant Contrastive Learning for Sequential Recommendation](https://arxiv.org/abs/2211.05290)

- [[WWW23] Mutual Wasserstein Discrepancy Minimization for Sequential Recommendation](https://dl.acm.org/doi/abs/10.1145/3543507.3583529)

- [[WWW23] Debiased Contrastive Learning for Sequential Recommendation](https://arxiv.org/pdf/2303.11780.pdf)

- [[SIGIR22] ELECRec: Training Sequential Recommenders as Discriminators](https://arxiv.org/pdf/2204.02011.pdf)

- [[Arxiv2021] Contrastive Learning for Sequential Recommendation](https://arxiv.org/pdf/2010.14395.pdf)

- [[Arxiv2021] Contrastive Self-supervised Sequential Recommendation with Robust Augmentation](https://arxiv.org/pdf/2108.06479.pdf)

- [[WSDM22] Contrastive Learning for Representation Degeneration Problem in Sequential Recommendation](https://arxiv.org/pdf/2110.05730.pdf)

- [[WWW22] Intent Contrastive Learning for Sequential Recommendation](https://dl.acm.org/doi/pdf/10.1145/3485447.3512090)

- [[CIKM20] S3-Rec: Self-Supervised Learning for Sequential Recommendation with Mutual Information Maximization](https://arxiv.org/abs/2008.07873.pdf)

## Negative sampling

- [[RecSys2023] gSASRec: Reducing Overconfidence in Sequential Recommendation Trained with Negative Sampling](https://eprints.gla.ac.uk/301348/)

- [[SIGIR23] Neighborhood-based Hard Negative Mining for Sequential Recommendation](https://arxiv.org/pdf/2306.10047.pdf)

## Data Augmentation

- [[AAAI23] Uniform Sequence Better: Time Interval Aware Data Augmentation for Sequential Recommendation](https://arxiv.org/pdf/2212.08262.pdf)

- [[SIGIR21] Counterfactual Data-Augmented Sequential Recommendation](https://dl.acm.org/doi/10.1145/3404835.3462855)

# Tool

- [[RUC] RecBole](https://github.com/RUCAIBox/RecBole)
![](https://img.shields.io/github/stars/RUCAIBox/RecBole.svg)

- [[NVIDIA] Transformers4Rec](https://github.com/NVIDIA-Merlin/Transformers4Rec)
![](https://img.shields.io/github/stars/NVIDIA-Merlin/Transformers4Rec.svg)

# Related Repository

- [Awesome-LLM4RS-Papers](https://github.com/nancheng58/Awesome-LLM4RS-Papers)
![](https://img.shields.io/github/stars/nancheng58/Awesome-LLM4RS-Papers.svg)
