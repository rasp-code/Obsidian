---
created: 2026-10-28
updated: 2026-10-28
---
The **natural logarithm** $\ln : (0, +\infty) \to \mathbb{R}$ is the inverse [[Function]] of the [[Exponential Function]]:

$$\ln(e^x) = x \quad \text{and} \quad e^{\ln y} = y \quad (y > 0)$$

**Logarithm in base $a$**
- $\log_a(x) = \dfrac{\ln x}{\ln a}$, inverse of $x \mapsto a^x$.

**Conditions**
- The argument must be strictly positive: $x > 0$.
- The base must satisfy $a > 0$ and $a \neq 1$.

**Properties**
- $\ln 1 = 0$ and $\ln e = 1$.
- $\ln(xy) = \ln x + \ln y$.
- $\ln(x/y) = \ln x - \ln y$.
- $\ln(x^k) = k \ln x$.
- Strictly increasing: $x < y \iff \ln x < \ln y$.
- $\lim_{x \to 0^+} \ln x = -\infty$ and $\lim_{x \to +\infty} \ln x = +\infty$.
- It grows slower than any positive power: $\lim_{x \to +\infty} \ln x / x^k = 0$ for every $k > 0$.
- $(\ln x)' = 1/x$ (see [[Derivative]]).