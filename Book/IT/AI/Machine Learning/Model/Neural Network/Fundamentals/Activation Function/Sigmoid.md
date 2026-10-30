---
created: 2026-10-27
updated: 2026-10-28
---
The **sigmoid** (logistic function) is the [[Activation Function]] that maps $\mathbb{R}$ to $(0, 1)$:

$$\sigma(z) = \frac{1}{1 + e^{-z}}, \qquad \sigma'(z) = \sigma(z)\big(1 - \sigma(z)\big)$$

**Properties**
- Its output can be read as a probability.
- $\sigma(-z) = 1 - \sigma(z)$.
- It saturates for large $|z|$, and $\sigma'(z) \leq 0.25$: causes the [[Vanishing Gradient]].
