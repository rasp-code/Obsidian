---
created: 2026-10-27
updated: 2026-10-28
---
**Optimization** is the problem of finding the [[Extremum]] of a [[Function]] over a set of allowed points:

$$\min_{x \in C} f(x)$$

**Elements**
- Decision variable: $x$.
- Objective function: the function $f$ to minimize.
- Feasible set: the set $C$ of allowed values of $x$.

**Types**
- Unconstrained: $C$ is the whole domain, e.g. $\mathbb{R}^n$.
- Constrained: $C = \{x \mid g_i(x) \leq 0,\ h_j(x) = 0\}$, with inequality constraints $g_i$ and equality constraints $h_j$.

**Terms**
- Solution (minimizer): a point $x^* \in C$ with $f(x^*) \leq f(x)$ for all $x \in C$.
- Optimal value: $f(x^*)$.
- $\arg\min_{x \in C} f(x)$ denotes the set of minimizers.

**Properties**
- Maximization is equivalent to minimization: $\max_x f(x) = -\min_x \big(-f(x)\big)$.
- A problem may have no solution, one solution, or several.