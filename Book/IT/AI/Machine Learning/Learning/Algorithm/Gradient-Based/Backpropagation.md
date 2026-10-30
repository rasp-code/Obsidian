---
created: 2026-10-27
updated: 2026-10-28
---
**Backpropagation** is the algorithm that computes the [[Gradient]] of the loss with respect to all [[Parameters]] of a [[Neural Network]], by applying the [[Chain Rule]] backward, from the output to the input.

**Steps**
- Forward pass: compute and store the activations of each layer, then the loss $J$.
- Backward pass: propagate the derivatives of $J$ from the last layer to the first.

**Formulas** (layer $\mathbf{z}^{(l)} = W^{(l)} \mathbf{h}^{(l-1)} + \mathbf{b}^{(l)}$, $\mathbf{h}^{(l)} = \varphi(\mathbf{z}^{(l)})$)
$$\boldsymbol{\delta}^{(l)} = \frac{\partial J}{\partial \mathbf{z}^{(l)}} = \big(W^{(l+1)\top} \boldsymbol{\delta}^{(l+1)}\big) \odot \varphi'(\mathbf{z}^{(l)})$$
$$\frac{\partial J}{\partial W^{(l)}} = \boldsymbol{\delta}^{(l)}\, \mathbf{h}^{(l-1)\top}, \qquad \frac{\partial J}{\partial \mathbf{b}^{(l)}} = \boldsymbol{\delta}^{(l)}$$

**Properties**
- Its cost is of the same order as a forward pass.
- It only computes gradients; the parameters are then changed by an [[Update Rule]].
