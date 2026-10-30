---
created: 2026-10-27
updated: 2026-10-28
---
A **dense layer** (fully connected layer) connects every input to every output neuron:

$$\mathbf{y} = \varphi(W\mathbf{x} + \mathbf{b}), \qquad W \in \mathbb{R}^{m \times n}$$

See [[Weight]], [[Bias]], [[Activation Function]].

**Properties**
- It has $m \times n + m$ parameters.
- Its input is a [[Vector]]: a feature map must be flattened first.
