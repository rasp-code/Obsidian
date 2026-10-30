---
created: 2026-10-23
updated: 2026-10-28
---
A **variational autoencoder (VAE)** is a generative [[Autoencoder]] whose encoder outputs a [[Probability Distribution]] over the latent space instead of a single point.

**Elements**
- Encoder: $q_\phi(\mathbf{z} \mid \mathbf{x}) = \mathcal{N}\big(\boldsymbol{\mu}, \mathrm{diag}(\boldsymbol{\sigma}^2)\big)$.
- Prior: $p(\mathbf{z}) = \mathcal{N}(0, I)$ (see [[Gaussian Distribution]]).
- Decoder: $p_\theta(\mathbf{x} \mid \mathbf{z})$.

**Objective** (maximize the ELBO)
$$\mathcal{L} = \mathbb{E}_{q_\phi(\mathbf{z} \mid \mathbf{x})}\big[\log p_\theta(\mathbf{x} \mid \mathbf{z})\big] - D_{KL}\big(q_\phi(\mathbf{z} \mid \mathbf{x}) \,\|\, p(\mathbf{z})\big)$$
- A reconstruction term, and a [[KL Divergence]] term pulling the latent distribution toward the prior.

**Reparameterization**
- $\mathbf{z} = \boldsymbol{\mu} + \boldsymbol{\sigma} \odot \boldsymbol{\varepsilon}$, $\boldsymbol{\varepsilon} \sim \mathcal{N}(0, I)$, so that gradients pass through sampling.

**Generation**
- Sample $\mathbf{z} \sim \mathcal{N}(0, I)$, then decode.
