---
created: 2026-10-28
updated: 2026-10-28
---
The **definite integral** of a [[Function]] $f$ over an interval $[a, b]$ is the limit of its Riemann sums:

$$\int_a^b f(x)\,dx = \lim_{\max \Delta x_i \to 0} \sum_{i=1}^{n} f(x_i^*)\,\Delta x_i$$

where $[a, b]$ is split into subintervals of widths $\Delta x_i$ and $x_i^*$ is a point of the $i$-th subinterval. The sum is a [[Limit]].

**Conditions**
- $f$ is bounded on $[a, b]$.
- Sufficient: $f$ is [[Continuity|continuous]] on $[a, b]$ (or continuous except at finitely many points).

**Geometric meaning**
- Signed area between the graph of $f$ and the horizontal axis: positive where $f > 0$, negative where $f < 0$.

**Properties**
- Linearity: $\int_a^b (\alpha f + \beta g) = \alpha \int_a^b f + \beta \int_a^b g$.
- Additivity: $\int_a^b f = \int_a^c f + \int_c^b f$.
- Orientation: $\int_b^a f = -\int_a^b f$, and $\int_a^a f = 0$.
- Monotonicity: $f \leq g \Rightarrow \int_a^b f \leq \int_a^b g$.
- $\left|\int_a^b f\right| \leq \int_a^b |f|$.

**Improper integrals**
- Infinite bound: $\int_a^{+\infty} f(x)\,dx = \lim_{M \to +\infty} \int_a^M f(x)\,dx$.
- The integral **converges** if this limit exists and is finite, and **diverges** otherwise.
- Example: $\int_1^{+\infty} \frac{dx}{x^2} = 1$ converges, while $\int_1^{+\infty} \frac{dx}{x}$ diverges.