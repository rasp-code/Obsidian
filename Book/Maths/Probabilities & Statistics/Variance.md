---
created: 2026-10-27
updated: 2026-10-28
---
The **variance** measures the dispersion of a [[Random Variable]] around its [[Expectation]]: it is the expected squared deviation from the mean.

$$\mathrm{Var}(X) = \mathbb{E}\big[(X - \mathbb{E}[X])^2\big] = \mathbb{E}[X^2] - \mathbb{E}[X]^2$$

The **standard deviation** is $\sigma = \sqrt{\mathrm{Var}(X)}$, expressed in the same unit as $X$.

**Properties**
- $\mathrm{Var}(X) \geq 0$, and $\mathrm{Var}(X) = 0$ if and only if $X$ is constant.
- $\mathrm{Var}(aX + b) = a^2\,\mathrm{Var}(X)$.
- If $X$ and $Y$ are [[Independence|independent]]: $\mathrm{Var}(X + Y) = \mathrm{Var}(X) + \mathrm{Var}(Y)$.