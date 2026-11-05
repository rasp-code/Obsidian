---
created: 2026-10-23
updated: 2026-10-28
---
The **gated recurrent unit (GRU)** is an [[RNN]] cell, a simplified version of the [[LSTM]] with two gates and no separate cell state.

Biases omitted:
$$\mathbf{z}_t = \sigma(W_z[\mathbf{h}_{t-1}, \mathbf{x}_t]), \qquad \mathbf{r}_t = \sigma(W_r[\mathbf{h}_{t-1}, \mathbf{x}_t])$$
$$\tilde{\mathbf{h}}_t = \tanh(W[\mathbf{r}_t \odot \mathbf{h}_{t-1}, \mathbf{x}_t]), \qquad \mathbf{h}_t = (1 - \mathbf{z}_t) \odot \mathbf{h}_{t-1} + \mathbf{z}_t \odot \tilde{\mathbf{h}}_t$$

**Gates**
- Update gate $\mathbf{z}_t$: how much of the state is replaced by the candidate $\tilde{\mathbf{h}}_t$.
- Reset gate $\mathbf{r}_t$: how much of the previous state is used to compute the candidate.

**Comparison**
- Fewer parameters than the [[LSTM]].
