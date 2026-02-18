# Voice Conversion with Optimal Transport

This page presents our paper:

**Title:** Discrete Optimal Transport is a Strong Audio Adversarial Attack
**Authors:** Anton Selitskiy, Akib Shahriyar, and Jishnuraj Prakasan  
**PDF:** [Download paper](https://arxiv.org/abs/2509.14959)
**Code:** [on GitHub](https://github.com/anton-selitskiy/DOTattack)

## Abstract
In this paper, we introduce the discrete optimal transport voice
conversion (*k*DOT-VC) method. Comparison with *k*NN-VC,
SinkVC, and Gaussian optimal transport (factorized MKL) demon-
strates stronger domain adaptation abilities of our method.
We use the probabilistic nature of optimal transport (OT) and
show that *k*DOT-VC is an effective black-box adversarial attack
against modern audio anti-spoofing countermeasures (CMs).
Our attack operates as a post-processing, distribution-alignment
step: frame-level WavLM embeddings of generated speech are
aligned to an unpaired bona fide pool via entropic OT and a top-
*k* barycentric projection, then decoded with a neural vocoder.
Ablation analysis indicates that distribution-level alignment is a
powerful and stable attack for deployed CMs.

## Code
[GitHub Repository](https://github.com/anton-selitskiy/DOTattack)

## Audio Samples
Link to examples, or embed a player using HTML.
