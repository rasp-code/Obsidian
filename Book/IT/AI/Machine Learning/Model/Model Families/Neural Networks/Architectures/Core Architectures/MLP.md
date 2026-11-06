---
created: 2026-10-23
updated: 2026-11-05
---
The simplest [[Deep Neural Network]], a [[Feedforward]] network made of [[Dense]] layers: every neuron receives the outputs of all neurons of the previous layer.

---

$$h^{(l)} = \varphi\big(W^{(l)} h^{(l-1)} + b^{(l)}\big), \qquad h^{(0)} = x, \quad \hat{y} = h^{(L)}$$

with $l = 1, \dots, L$ the layers, $W^{(l)}$ and $b^{(l)}$ the [[Weight|weights]] and [[Bias|biases]] of layer $l$, and $\varphi$ the [[Activation Function]].