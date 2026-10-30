---
created: 2026-09-11
updated: 2026-10-28
---
A **neural network** is a [[Model]] made of interconnected units called **neurons**, organized in layers, that computes a [[Function]] of its [[Input]].

**Neuron**
- It computes a weighted sum of its inputs plus a bias, then applies an [[Activation Function]] $\varphi$ (see [[Weight]], [[Bias]], [[Dot Product]]):
$$a = \varphi(\mathbf{w}^\top \mathbf{x} + b)$$

**Layers**
- Input layer: receives the input $\mathbf{x}$.
- Hidden layers: intermediate layers.
- Output layer: produces the [[Output]].
- The network is the composition of the layer functions: $f = f_L \circ \dots \circ f_1$.

**Properties**
- Its [[Parameters]] are the weights and biases of all neurons.
- If all activation functions are differentiable, the network is differentiable with respect to its parameters.

**Subnotes**
- [[Book/IT/AI/Machine Learning/Model/Neural Network/Fundamentals/Fundamentals|Fundamentals]]: building blocks of neural networks.
- [[Architectures]]: ways of organizing layers.
