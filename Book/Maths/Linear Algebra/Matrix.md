---
created: 2026-10-27
updated: 2026-10-28
---
A **matrix** is a rectangular array of numbers with $m$ rows and $n$ columns, written $A \in \mathbb{R}^{m \times n}$, with entries $a_{ij}$.

A matrix represents a [[Linear Map]] $\mathbb{R}^n \to \mathbb{R}^m$: it transforms a [[Vector]] $\mathbf{x}$ into $A\mathbf{x}$, where
$$(A\mathbf{x})_i = \sum_j a_{ij}\,x_j$$

**Operations**
- Addition and scalar multiplication: entry-wise.
- Product: $(AB)_{ij} = \sum_k a_{ik}\,b_{kj}$, defined if the number of columns of $A$ equals the number of rows of $B$. In general $AB \neq BA$.
- Transpose: $(A^\top)_{ij} = a_{ji}$.

**Special matrices**
- Identity $I$: $I\mathbf{x} = \mathbf{x}$.
- Square: $m = n$.
- Symmetric: $A = A^\top$.
- Invertible: there exists $A^{-1}$ such that $AA^{-1} = A^{-1}A = I$.