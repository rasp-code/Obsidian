---
created: 2026-09-11
updated: 2026-11-05
---
A network that processes grid-structured data, mostly images, by detecting local patterns with [[Kernel|kernels]] shared across positions.

---

## Description

Core operation, the [[Convolution]], shown in 2D: a small [[Kernel]] $k$ slides over the input $x$, with [[Bias|bias]] $b$ and activation $\varphi$.

$$y_{i,j} = \varphi\Big(\sum_{m,n} k_{m,n}\, x_{i+m,\,j+n} + b\Big)$$

- The [[Stride]] sets the step of each slide, and the [[Padding]] adds a border around the input.
- Each kernel produces a [[Feature Map]], the grid of its responses.
- Data has several [[Channel|channels]], such as red, green and blue for an image, and the feature maps of one layer become the channels of the next.

A CNN typically stacks:

- [[Convolutional]] layers: apply the kernels to detect local patterns
- [[Activation Function]]: adds nonlinearity after each convolution
- [[Pooling]] layers: shrink the grid, keeping the strongest or average response
- [[Normalization]] layers: stabilize training
- [[Dense]] layers: at the end, turn the detected features into the output

Early layers detect simple patterns such as edges, and deeper ones combine them into complex shapes.