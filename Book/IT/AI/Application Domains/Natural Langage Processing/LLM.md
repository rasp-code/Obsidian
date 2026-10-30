---
created: 2026-10-27
updated: 2026-10-28
---
A **large language model (LLM)** is a [[Transformer]] with a very large number of [[Parameters]], trained to predict the next token of a text.

**Objective**
- Autoregressive factorization of a sequence, learned by minimizing the [[Cross-Entropy]] of the next token:
$$P(x_1, \dots, x_T) = \prod_{t=1}^{T} P(x_t \mid x_{<t})$$

**Training**
- [[Pre-Training]] by [[Self-Supervised Learning]] on a large text corpus.
- [[Fine-Tuning]] on instructions and human preferences.

**Generation**
- Tokens are sampled one by one, each conditioned on the previous ones.
