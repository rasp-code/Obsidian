---
created: 2026-10-27
updated: 2026-10-28
---
The **derivative** of a [[Function]] $f : \mathbb{R} \to \mathbb{R}$ at a point $x$ measures the instantaneous rate of change of $f$ at $x$. It is defined as a [[Limit]]:

$$f'(x) = \frac{df}{dx} = \lim_{h \to 0} \frac{f(x+h) - f(x)}{h}$$

**Conditions**
- $f$ is defined on a neighborhood of $x$.
- The limit exists and is finite. $f$ is then **differentiable** at $x$.

**Geometric meaning**
- $f'(x)$ is the slope of the tangent line to the graph of $f$ at $x$.

**Properties**
- If $f$ is differentiable at $x$, then $f$ is [[Continuity|continuous]] at $x$.
- The converse is false: $f(x) = |x|$ is continuous but not differentiable at $0$.
- Linearity: $(af + bg)' = af' + bg'$.
- Product: $(fg)' = f'g + fg'$.
- Quotient: $(f/g)' = \dfrac{f'g - fg'}{g^2}$, where $g \neq 0$.

**Common derivatives**
- $(x^n)' = nx^{n-1}$.
- $(e^x)' = e^x$.
- $(\ln x)' = 1/x$.