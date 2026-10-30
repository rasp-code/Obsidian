---
created: 2026-10-22
updated: 2026-10-28
---
**Gradient boosting** is an ensemble method that builds models sequentially, each new one (a small [[Decision Tree]]) fitting the errors of the current ensemble:

$$F_m(x) = F_{m-1}(x) + \eta\, h_m(x)$$

**Principle**
- $h_m$ is fitted to the pseudo-residuals, the negative [[Gradient]] of the loss with respect to the current predictions:
$$r_i = -\frac{\partial L\big(y_i, F_{m-1}(x_i)\big)}{\partial F_{m-1}(x_i)}$$
- For the squared error, these are the residuals $y_i - F_{m-1}(x_i)$.
- It is [[GD]] in function space, with step $\eta$ (shrinkage).

**Properties**
- It reduces bias; too many trees lead to [[Overfitting]].

**Comparison**
- [[Random Forest]] builds independent trees to reduce variance.
