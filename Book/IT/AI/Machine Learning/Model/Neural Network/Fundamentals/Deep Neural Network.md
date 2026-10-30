---
created: 2026-10-27
updated: 2026-10-28
---
A **deep neural network** is a [[Neural Network]] with several hidden layers, so that the [[Function]] it computes is a long composition of layer functions:

$$f = f_L \circ f_{L-1} \circ \dots \circ f_1$$

**Properties**
- Depth is the number of layers; at least two hidden layers is the usual convention.
- Successive layers compute increasingly composed functions of the input.
- Depth adds expressive power only with a nonlinear [[Activation Function]].

**Comparison**
- A shallow network has a single hidden layer.
