---
created: 2026-10-27
updated: 2026-10-28
---
The **conditional probability** of an [[Event]] $A$ given an event $B$ is the probability that $A$ occurs knowing that $B$ has occurred, according to a [[Probability Measure]] $P$:

$$P(A \mid B) = \frac{P(A \cap B)}{P(B)}$$

**Condition**
- $P(B) > 0$.

**Properties**
- $P(\cdot \mid B)$ is itself a probability measure on $\Omega$.
- Product rule: $P(A \cap B) = P(A \mid B)\,P(B) = P(B \mid A)\,P(A)$.

**For random variables**
- $p(y \mid x) = \dfrac{p(x, y)}{p(x)}$, with $p(x, y)$ the joint distribution and $p(x)$ the marginal distribution, for $p(x) > 0$.