---
created: 2026-10-27
updated: 2026-10-28
---
The **hyperbolic tangent** is the [[Activation Function]] that maps $\mathbb{R}$ to $(-1, 1)$:

$$\tanh(z) = \frac{e^{z} - e^{-z}}{e^{z} + e^{-z}} = 2\sigma(2z) - 1, \qquad \tanh'(z) = 1 - \tanh^2(z)$$

**Properties**
- Zero-centered, unlike the [[Sigmoid]].
- It saturates for large $|z|$: causes the [[Vanishing Gradient]].
