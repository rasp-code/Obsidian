---
created: 2026-09-11
updated: 2026-10-28
---
A **recurrent neural network (RNN)** is a [[Neural Network]] for sequences that maintains a hidden state, updated at each time step with the same weights:

$$\mathbf{h}_t = \tanh(W_h \mathbf{h}_{t-1} + W_x \mathbf{x}_t + \mathbf{b}), \qquad \hat{\mathbf{y}}_t = W_y \mathbf{h}_t$$

**Properties**
- Handles sequences of variable length.
- Trained by backpropagation through time, on the unrolled network.
- Suffers from the [[Vanishing Gradient]] and [[Exploding Gradient]]: long-term dependencies are hard to learn.

**Gated cells**
- [[LSTM]]: cell state with forget, input and output gates.
- [[GRU]]: simplified version with update and reset gates.
