---
created: 2026-10-25
updated: 2026-10-28
---
**Density estimation** is the [[Structure]] task of estimating the [[Probability Distribution]] $p(x)$ that generated the examples of a [[Dataset]].

**Formulation**
- Find $\hat{p}(x)$ from samples $x_1, \dots, x_N$ such that $\hat{p}$ approximates $p$.

**Conditions** (for $\hat{p}$ to be a valid density)
- $\hat{p}(x) \geq 0$ for all $x$.
- $\int \hat{p}(x)\,dx = 1$ (see [[Integral]]).

**Evaluation**
- Average log-likelihood on held-out data (see [[Logarithm]]):
$$\frac{1}{N}\sum_{i=1}^{N} \ln \hat{p}(x_i)$$
