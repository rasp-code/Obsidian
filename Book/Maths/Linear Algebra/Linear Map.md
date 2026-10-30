---
created: 2026-10-28
updated: 2026-10-28
---
A **linear map** between two [[Vector Space|vector spaces]] $V$ and $W$ over the same scalars is a [[Function]] $f : V \to W$ such that, for all $u, v \in V$ and $a \in \mathbb{K}$:

- Additivity: $f(u + v) = f(u) + f(v)$.
- Homogeneity: $f(av) = a\,f(v)$.

**Properties**
- $f(0) = 0$.
- It preserves [[Linear Combination|linear combinations]]: $f\left(\sum_i a_i v_i\right) = \sum_i a_i f(v_i)$.
- The composition of linear maps is linear.
- It is fully determined by the images of the vectors of a basis.
- In finite dimension, once bases are chosen, it is represented by a matrix: $f(\mathbf{x}) = A\mathbf{x}$.

**Examples**
- Rotation, scaling and reflection of the plane.
- Differentiation of polynomials.