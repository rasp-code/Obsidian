---
created: 2026-10-28
updated: 2026-10-28
---
The **bias-variance tradeoff** is the decomposition of the expected error of a model into bias, variance and noise, where bias and variance vary in opposite directions with model complexity.

For $y = f(x) + \varepsilon$ with $\mathrm{Var}(\varepsilon) = \sigma^2$, and the squared error:
$$\mathbb{E}\big[(y - \hat{f}(x))^2\big] = \mathrm{Bias}\big[\hat{f}(x)\big]^2 + \mathrm{Var}\big[\hat{f}(x)\big] + \sigma^2$$

See [[Expectation]], [[Variance]].

**Terms**
- Bias: $\mathbb{E}[\hat{f}(x)] - f(x)$, error due to wrong assumptions of the model.
- Variance: sensitivity of $\hat{f}$ to the training set.
- Noise $\sigma^2$: irreducible error.

**Properties**
- Increasing complexity decreases bias and increases variance.
- High bias leads to [[Underfitting]]; high variance to [[Overfitting]].
