---
created: 2026-10-27
updated: 2026-10-28
---
A **convolutional layer** applies learned filters (kernels) that slide over the input and compute a weighted sum at each position, producing one feature map per filter:

$$Y^{(k)}_{i,j} = \sum_{c} \sum_{m} \sum_{n} K^{(k)}_{c,m,n}\, X_{c,\, i+m,\, j+n} + b^{(k)}$$

**Hyperparameters**
- Kernel size $k$ and number of filters (output channels).
- Stride $s$: step between positions.
- Padding $p$: zeros added at the border.
- Output size for an input of size $n$:
$$\left\lfloor \frac{n + 2p - k}{s} \right\rfloor + 1$$

**Properties**
- Each filter has $k \times k \times C_{\text{in}}$ [[Weight|weights]] and one [[Bias]], independently of the input size.
