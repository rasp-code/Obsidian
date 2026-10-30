---
created: 2026-10-23
updated: 2026-10-28
---
The **perceptron** is the simplest [[Neural Network]]: a single neuron with a step [[Activation Function]], used as a binary linear classifier (see [[Classification]]).

$$\hat{y} = H(\mathbf{w}^\top \mathbf{x} + b), \qquad H(z) = \begin{cases} 1 & z \geq 0 \\ 0 & z < 0 \end{cases}$$

See [[Weight]], [[Bias]], [[Dot Product]].

**Decision boundary**
- The hyperplane $\{\mathbf{x} \mid \mathbf{w}^\top \mathbf{x} + b = 0\}$.

**Perceptron learning rule** (an [[Update Rule]])
- For a labeled example $(\mathbf{x}, y)$ with $y \in \{0, 1\}$, and a step size $\eta > 0$:
$$\mathbf{w} \leftarrow \mathbf{w} + \eta\,(y - \hat{y})\,\mathbf{x}, \qquad b \leftarrow b + \eta\,(y - \hat{y})$$
- No change if the prediction is correct.

**Conditions and limits**
- It only separates classes separable by a hyperplane (linearly separable).
- If the data is linearly separable, the rule converges in a finite number of updates; otherwise, it does not converge.
