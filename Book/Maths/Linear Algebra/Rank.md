---
created: 2026-10-28
updated: 2026-10-28
---
The **rank** of a [[Matrix]] $A \in \mathbb{R}^{m \times n}$ is the [[Dimension]] of the [[Span]] of its columns (its column space, or image):

$$\mathrm{rank}(A) = \dim \mathrm{Span}(\text{columns of } A)$$

Equivalently, the rank of a [[Linear Map]] is the dimension of its image.

**Characterization**
- It is the maximal number of [[Linear Independence|linearly independent]] columns, which equals the maximal number of linearly independent rows.

**Properties**
- $\mathrm{rank}(A) = \mathrm{rank}(A^\top)$ (see [[Transpose]]).
- $\mathrm{rank}(A) \leq \min(m, n)$.
- $\mathrm{rank}(AB) \leq \min(\mathrm{rank}(A), \mathrm{rank}(B))$.
- $A$ has **full rank** if $\mathrm{rank}(A) = \min(m, n)$.
- Rank-nullity: $\mathrm{rank}(A) + \dim \ker(A) = n$, where $\ker(A) = \{\mathbf{x} : A\mathbf{x} = 0\}$.