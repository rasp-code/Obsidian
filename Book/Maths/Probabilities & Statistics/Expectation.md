---
created: 2026-10-27
updated: 2026-10-28
---
The **expectation** $\mathbb{E}[X]$ of a [[Random Variable]] is the average of its values weighted by their probabilities, according to its [[Probability Distribution]].

$$\mathbb{E}[X] = \sum_x x\,p(x) \qquad \text{(discrete)}$$
$$\mathbb{E}[X] = \int_{-\infty}^{+\infty} x\,f(x)\,dx \qquad \text{(continuous)}$$

**Existence**
- The sum or integral must converge absolutely; otherwise the expectation is undefined.

**Function of a variable**
- $\mathbb{E}[g(X)] = \sum_x g(x)\,p(x)$ (discrete), or $\int g(x)\,f(x)\,dx$ (continuous).

**Properties**
- Linearity: $\mathbb{E}[aX + bY + c] = a\,\mathbb{E}[X] + b\,\mathbb{E}[Y] + c$, whether or not $X$ and $Y$ are independent.
- Monotonicity: $X \leq Y \Rightarrow \mathbb{E}[X] \leq \mathbb{E}[Y]$.
- If $X$ and $Y$ are [[Independence|independent]]: $\mathbb{E}[XY] = \mathbb{E}[X]\,\mathbb{E}[Y]$.