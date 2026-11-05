---
created: 2026-10-23
updated: 2026-10-28
---
A **support vector machine (SVM)** is a classifier that finds the hyperplane separating two classes with the largest **margin**.

**Hard margin** (linearly separable data, $y_i \in \{-1, +1\}$)
$$\min_{\mathbf{w}, b} \frac{1}{2}\|\mathbf{w}\|^2 \quad \text{s.t.} \quad y_i(\mathbf{w}^\top \mathbf{x}_i + b) \geq 1 \;\; \forall i$$
- The margin width is $2 / \|\mathbf{w}\|$.

**Soft margin** (errors allowed, hinge [[Loss Function]])
$$\min_{\mathbf{w}, b} \frac{1}{2}\|\mathbf{w}\|^2 + C \sum_{i=1}^{N} \max\big(0,\; 1 - y_i(\mathbf{w}^\top \mathbf{x}_i + b)\big)$$
- $C$ trades margin width against errors.

**Kernel trick**
- [[Dot Product|Dot products]] are replaced by a kernel $k(\mathbf{x}, \mathbf{x}')$, giving nonlinear boundaries without computing features explicitly.

**Properties**
- The solution depends only on the **support vectors**: the points on or inside the margin.
- The problem is [[Convexity|convex]]: unique optimum.
