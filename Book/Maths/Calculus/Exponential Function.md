---
created: 2026-10-28
updated: 2026-10-28
---
The **exponential function** $\exp : \mathbb{R} \to (0, +\infty)$, written $\exp(x) = e^x$, is the [[Function]] defined by

$$e^x = \sum_{n=0}^{\infty} \frac{x^n}{n!} = \lim_{n \to \infty} \left(1 + \frac{x}{n}\right)^n$$

where $e = e^1 \approx 2.71828$ is Euler's number. Both expressions are [[Limit]]s.

**Characterization**
- It is the unique [[Derivative|differentiable]] function such that $f' = f$ and $f(0) = 1$.

**Properties**
- $e^x > 0$ for all $x$.
- $e^0 = 1$.
- $e^{x+y} = e^x e^y$.
- $e^{-x} = 1 / e^x$.
- $(e^x)' = e^x$.
- Strictly increasing, and a bijection from $\mathbb{R}$ onto $(0, +\infty)$.
- $\lim_{x \to -\infty} e^x = 0$ and $\lim_{x \to +\infty} e^x = +\infty$.
- It grows faster than any polynomial: $\lim_{x \to +\infty} x^k / e^x = 0$ for every $k$.

**General base**
- For $a > 0$: $a^x = e^{x \ln a}$.