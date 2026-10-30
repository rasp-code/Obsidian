---
created: 2026-10-27
updated: 2026-10-28
---
The **rectified linear unit (ReLU)** is the [[Activation Function]]:

$$\mathrm{ReLU}(z) = \max(0, z), \qquad \mathrm{ReLU}'(z) = \begin{cases} 1 & z > 0 \\ 0 & z < 0 \end{cases}$$

**Properties**
- Values in $[0, +\infty)$.
- Gradient $1$ for positive inputs: no saturation, which limits the [[Vanishing Gradient]].
- A neuron whose input is always negative gets zero gradient and stops learning ("dying ReLU").
