---
created: 2026-10-27
updated: 2026-10-28
---
The **probability distribution** of a [[Random Variable]] $X$ is the [[Probability Measure]] $P_X$ it induces on its set of values $E$:

$$P_X(B) = P(X \in B) = P(X^{-1}(B))= P(\{\omega \in \Omega : X(\omega) \in B\})$$

It describes how probability is spread over the values $X$ can take.

**Discrete case**: probability mass function $p(x) = P(X = x)$.
- $p(x) \geq 0$ for all $x$.
- $\sum_x p(x) = 1$.
- $P(X \in B) = \sum_{x \in B} p(x)$.

**Continuous case**: probability density function $f(x)$.
- $f(x) \geq 0$ for all $x$.
- $\int_{-\infty}^{+\infty} f(x)\,dx = 1$.
- $P(a \leq X \leq b) = \int_a^b f(x)\,dx$.
- $P(X = x) = 0$ for any single value; *only areas under the density are probabilities.*
- $f(x)$ can exceed 1.

**Cumulative distribution function**: $F(x) = P(X \leq x)$, valid for discrete and continuous variables.
- Non-decreasing.
- $\lim_{x \to -\infty} F(x) = 0$ and $\lim_{x \to +\infty} F(x) = 1$.
- Right-continuous.