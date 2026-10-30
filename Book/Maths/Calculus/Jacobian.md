---
created: 2026-10-27
updated: 2026-10-28
---
The **Jacobian** of a vector-valued function $\mathbf{f} : \mathbb{R}^n \to \mathbb{R}^m$ is the [[Matrix]] of all its first-order [[Partial Derivative|partial derivatives]]:

$$J_{\mathbf{f}}(\mathbf{x}) = \begin{pmatrix}
\dfrac{\partial f_1}{\partial x_1} & \cdots & \dfrac{\partial f_1}{\partial x_n} \\
\vdots & \ddots & \vdots \\
\dfrac{\partial f_m}{\partial x_1} & \cdots & \dfrac{\partial f_m}{\partial x_n}
\end{pmatrix} \in \mathbb{R}^{m \times n}$$

Row $i$ is the transpose of the [[Gradient]] of $f_i$.

**Properties**
- It is the best local linear approximation of $\mathbf{f}$ (first-order [[Taylor Expansion|Taylor]] expansion): $\mathbf{f}(\mathbf{x} + \mathbf{h}) \approx \mathbf{f}(\mathbf{x}) + J_{\mathbf{f}}(\mathbf{x})\,\mathbf{h}$.
- For $m = 1$, it is the transpose of the gradient.
- If $m = n$, $\det J_{\mathbf{f}}(\mathbf{x})$ gives the local volume scaling factor of $\mathbf{f}$ at $\mathbf{x}$.