---
created: 2026-10-28
updated: 2026-10-28
---
Two vectors $x, y$ of an [[Inner Product]] space are **orthogonal**, written $x \perp y$, if $\langle x, y \rangle = 0$.

**Families**
- Orthogonal family: its vectors are pairwise orthogonal.
- Orthonormal family: orthogonal, and each vector has [[Norm]] $1$.

**Properties**
- The zero vector is orthogonal to every vector.
- An orthogonal family of nonzero vectors is [[Linear Independence|linearly independent]].
- Pythagorean theorem: if $x \perp y$ then $\|x + y\|^2 = \|x\|^2 + \|y\|^2$.

**Orthogonal complement**
- For a [[Subspace]] $W$: $W^\perp = \{x \mid \langle x, w \rangle = 0 \ \forall w \in W\}$.
- $W^\perp$ is a subspace, and $W \cap W^\perp = \{0\}$.
- In finite dimension, $\dim W + \dim W^\perp = \dim V$ (see [[Dimension]]).