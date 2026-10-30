---
created: 2026-10-27
updated: 2026-10-28
---
The **Gaussian (normal) distribution** $\mathcal{N}(\mu, \sigma^2)$ is a continuous [[Probability Distribution]] with density

$$f(x) = \frac{1}{\sigma\sqrt{2\pi}} \exp\!\left(-\frac{(x-\mu)^2}{2\sigma^2}\right)$$

**Parameters**
- $\mu$: mean, equal to the [[Expectation]] of $X$.
- $\sigma^2$: variance, equal to the [[Variance]] of $X$ ($\sigma > 0$).

**Properties**
- Symmetric and bell-shaped, centered at $\mu$.
- Approximately 68%, 95% and 99.7% of the probability lies within $1\sigma$, $2\sigma$ and $3\sigma$ of $\mu$.
- Standard normal: $\mathcal{N}(0, 1)$. Any $X \sim \mathcal{N}(\mu, \sigma^2)$ becomes standard via $Z = (X - \mu)/\sigma$.
- Stable under linear transformation: $aX + b \sim \mathcal{N}(a\mu + b,\ a^2\sigma^2)$.
- The sum of [[Independence|independent]] Gaussian variables is Gaussian.

**Multivariate case**
- $\mathcal{N}(\boldsymbol{\mu}, \Sigma)$, with mean vector $\boldsymbol{\mu}$ and covariance matrix $\Sigma$.