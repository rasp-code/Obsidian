---
created: 2026-10-25
updated: 2026-10-28
---
An **activation function** $\varphi : \mathbb{R} \to \mathbb{R}$ is a [[Function]] applied to the weighted sum $z$ of a neuron, to produce its output $a = \varphi(z)$. It is applied element-wise to a [[Vector]] of pre-activations.

**Purpose**
- It introduces nonlinearity. Without it, a composition of layers is a composition of [[Linear Map|linear maps]], which is linear: depth adds no expressive power.

**Conditions**
- Nonlinear.
- [[Derivative|Differentiable]] almost everywhere, for gradient-based learning.

**Functions**
- [[ReLU]]: $\max(0, z)$.
- [[Sigmoid]]: values in $(0, 1)$.
- [[Tanh]]: values in $(-1, 1)$.
- [[SoftMax]]: vector → probability distribution.
