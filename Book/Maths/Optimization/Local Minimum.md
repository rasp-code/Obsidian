---
created: 2026-10-27
updated: 2026-10-28
---
A point $x^*$ is a **local minimum** of a function $f$ if there exists a neighborhood of $x^*$ in which no point has a lower value:

$$\exists\, \varepsilon > 0,\ \forall x \text{ with } \|x - x^*\| < \varepsilon : \quad f(x^*) \leq f(x)$$

**Necessary condition** (differentiable $f$): $\nabla f(x^*) = 0$, i.e. $x^*$ is a critical point. This condition is not sufficient: a critical point can also be a local maximum or a saddle point.

A local minimum is not necessarily a [[Global Minimum]].