---
created: 2026-10-28
updated: 2026-10-28
---
The **higher-order derivatives** of a [[Function]] $f$ are obtained by differentiating repeatedly.

**Definition**
- $f'' = (f')'$, and more generally $f^{(n)} = \big(f^{(n-1)}\big)'$, with $f^{(0)} = f$.
- Notation: $f^{(n)}(x) = \dfrac{d^n f}{dx^n}(x)$.

**Conditions**
- $f^{(n)}(x)$ exists if $f^{(n-1)}$ exists on a neighborhood of $x$ and is [[Derivative|differentiable]] at $x$.

**Smoothness classes**
- $C^n$: $f$ is $n$ times differentiable and $f^{(n)}$ is [[Continuity|continuous]].
- $C^\infty$: $f$ is $C^n$ for every $n$.

**Meaning**
- $f'$ is the rate of change of $f$.
- $f''$ is the rate of change of $f'$; its sign gives the curvature of the graph (convex where $f'' \geq 0$, concave where $f'' \leq 0$).

**Example**
- For $f(x) = x^3$: $f'(x) = 3x^2$, $f''(x) = 6x$, $f'''(x) = 6$, $f^{(4)}(x) = 0$.