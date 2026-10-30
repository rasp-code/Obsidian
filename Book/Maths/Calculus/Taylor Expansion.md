---
created: 2026-10-28
updated: 2026-10-28
---
The **Taylor expansion** approximates a [[Function]] $f$ near a point $a$ by a polynomial built from its [[Higher-Order Derivative|derivatives]] at $a$.

**Taylor polynomial of order $n$**
$$T_n(x) = \sum_{k=0}^{n} \frac{f^{(k)}(a)}{k!}\,(x-a)^k$$

**Conditions**
- $f$ is $n$ times [[Derivative|differentiable]] at $a$.

**Remainder**
- $f(x) = T_n(x) + R_n(x)$.
- Peano form: $R_n(x) = o\big((x-a)^n\big)$, i.e. $R_n(x)/(x-a)^n \to 0$ as $x \to a$ (see [[Limit]]).
- Lagrange form: if $f^{(n+1)}$ exists, $R_n(x) = \dfrac{f^{(n+1)}(\xi)}{(n+1)!}(x-a)^{n+1}$ for some $\xi$ between $a$ and $x$.

**Low orders**
- Order 1 (linear approximation): $f(x) \approx f(a) + f'(a)(x-a)$.
- Order 2 (quadratic approximation): $f(x) \approx f(a) + f'(a)(x-a) + \tfrac{1}{2} f''(a)(x-a)^2$.

**Particular case**
- Maclaurin expansion: $a = 0$.

**Examples** (at $a = 0$)
- $e^x \approx 1 + x + \dfrac{x^2}{2} + \dfrac{x^3}{6}$.
- $\ln(1+x) \approx x - \dfrac{x^2}{2} + \dfrac{x^3}{3}$.

**Scope**
- This note covers functions of one variable.