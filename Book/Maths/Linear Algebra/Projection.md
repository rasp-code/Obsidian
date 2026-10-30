---
created: 2026-10-28
updated: 2026-10-28
---
A **projection** is a [[Linear Map]] $P : V \to V$ such that $P \circ P = P$ (idempotent). Its image is the set of vectors it leaves unchanged.

**Orthogonal projection** onto a [[Vector Subspace]] $W$ of an [[Inner Product]] space $V$: the projection $P_W$ such that, for every $x \in V$, $p = P_W(x)$ is the unique vector of $W$ satisfying

$$x - p \in W^\perp$$

(see [[Orthogonality]]).

**Properties**
- Decomposition: $x = p + (x - p)$ with $p \in W$ and $x - p \in W^\perp$.
- Best approximation: $\|x - p\| \leq \|x - w\|$ for all $w \in W$ (see [[Norm]]).
- $P_W^\top = P_W$ and $P_W^2 = P_W$ in matrix form.
- $\|P_W(x)\| \leq \|x\|$.

**Formulas**
- Onto the line spanned by a nonzero $a$: $P(x) = \dfrac{\langle x, a \rangle}{\langle a, a \rangle}\,a$.
- Onto the span of an orthonormal family $u_1, \dots, u_k$: $P(x) = \sum_{i=1}^{k} \langle x, u_i \rangle\,u_i$.
- Onto the column space of a matrix $A$ with linearly independent columns: $P = A(A^\top A)^{-1}A^\top$ (see [[Inverse Matrix]], [[Transpose]]).