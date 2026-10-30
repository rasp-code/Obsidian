---
created: 2026-10-27
updated: 2026-10-28
---
A **generative adversarial network (GAN)** is a generative model made of two [[Neural Network|neural networks]] trained against each other.

**Elements**
- Generator $G$: transforms random noise $z$ into a sample $G(z)$.
- Discriminator $D$: estimates the probability that a sample is real.

**Objective** (minimax game)
$$\min_G \max_D \; \mathbb{E}_{x \sim p_{\text{data}}}\big[\log D(x)\big] + \mathbb{E}_{z \sim p_z}\big[\log\big(1 - D(G(z))\big)\big]$$

**Properties**
- $G$ learns to fool $D$, and $D$ learns to detect generated samples.
- Training is unstable; the generator may produce little diversity (mode collapse).
- It gives no explicit density $p(x)$.
