---
created: 2026-10-23
updated: 2026-10-28
---
A **multilayer perceptron (MLP)** is a [[Neural Network]] made of fully connected layers of neurons, in which information flows only forward, from input to output.

**Layer computation**
$$\mathbf{h}^{(l)} = \varphi\big(W^{(l)} \mathbf{h}^{(l-1)} + \mathbf{b}^{(l)}\big), \qquad \mathbf{h}^{(0)} = \mathbf{x}$$
- $W^{(l)}$: [[Matrix]] of [[Weight|weights]] of layer $l$.
- $\mathbf{b}^{(l)}$: [[Vector]] of [[Bias|biases]].
- $\varphi$: [[Activation Function]], applied element-wise.

**Properties**
- Feedforward: no cycles.
- Fully connected: each neuron receives all outputs of the previous layer.
- At least one hidden layer.
- Its neurons generalize those of the [[Perceptron]], with differentiable activations instead of a step.
