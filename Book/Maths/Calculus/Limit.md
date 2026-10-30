---
created: 2026-10-28
updated: 2026-10-28
---
The **limit** of a [[Function]] $f$ at a point $a$ is the value $L$ that $f(x)$ approaches as $x$ approaches $a$, with $x \neq a$.

**Formal definition**
$$\lim_{x \to a} f(x) = L \iff \forall \varepsilon > 0,\ \exists \delta > 0,\ \forall x \text{ with } 0 < |x - a| < \delta : \ |f(x) - L| < \varepsilon$$

**Conditions**
- $f$ is defined on a neighborhood of $a$, except possibly at $a$.
- The value $f(a)$, if it exists, plays no role.

**Variants**
- One-sided limits: $\lim_{x \to a^-} f(x)$ and $\lim_{x \to a^+} f(x)$.
- Limit at infinity: $\lim_{x \to +\infty} f(x) = L$ if $\forall \varepsilon > 0,\ \exists M,\ \forall x > M : |f(x) - L| < \varepsilon$.
- Infinite limit: $f(x)$ grows without bound ($+\infty$) or decreases without bound ($-\infty$).

**Properties**
- Uniqueness: if the limit exists, it is unique.
- The limit at $a$ exists if and only if both one-sided limits exist and are equal.
- Sum, product: $\lim (f + g) = \lim f + \lim g$ and $\lim (fg) = \lim f \cdot \lim g$.
- Quotient: $\lim (f/g) = \lim f / \lim g$ if $\lim g \neq 0$.
- Squeeze theorem: if $g \leq f \leq h$ near $a$ and $\lim g = \lim h = L$, then $\lim f = L$.