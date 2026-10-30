---
created: 2026-10-23
updated: 2026-10-28
---
A **diffusion model** is a generative model that learns to reverse a gradual noising process: it generates data by progressively denoising pure noise.

**Forward process** (fixed)
- [[Gaussian Distribution|Gaussian]] noise is added over $T$ steps until the data becomes pure noise, with $\bar{\alpha}_t$ decreasing from $1$ to almost $0$:
$$x_t = \sqrt{\bar{\alpha}_t}\, x_0 + \sqrt{1 - \bar{\alpha}_t}\, \varepsilon, \qquad \varepsilon \sim \mathcal{N}(0, I)$$

**Reverse process** (learned)
- A [[Neural Network]] $\varepsilon_\theta(x_t, t)$ predicts the added noise, trained with the loss $\|\varepsilon - \varepsilon_\theta(x_t, t)\|^2$.
- Generation starts from $x_T \sim \mathcal{N}(0, I)$ and denoises step by step down to $x_0$.

**Properties**
- Sampling is slow: one network evaluation per denoising step.
