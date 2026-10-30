---
created: 2026-10-28
updated: 2026-10-28
---
The **fundamental theorem of calculus** links the [[Derivative]] and the [[Integral]].

**Antiderivative**
- An antiderivative of $f$ on an interval is a [[Function]] $F$ such that $F' = f$.
- Two antiderivatives of $f$ differ by a constant.
- The indefinite integral $\int f(x)\,dx = F(x) + C$ denotes the set of all antiderivatives.

**Conditions**
- $f$ is [[Continuity|continuous]] on an interval $[a, b]$.

**Part 1**
- The function $F(x) = \int_a^x f(t)\,dt$ is differentiable on $[a, b]$ and $F'(x) = f(x)$.
- Hence every continuous function has an antiderivative.

**Part 2**
- If $F$ is any antiderivative of $f$, then
$$\int_a^b f(x)\,dx = F(b) - F(a)$$

**Consequences**
- Differentiation and integration are inverse operations.
- A definite integral can be computed from an antiderivative, without computing a limit of sums.