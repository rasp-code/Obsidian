---
created: 2026-09-11
updated: 2026-10-28
---
**Long short-term memory (LSTM)** is an [[RNN]] cell that uses gates and a cell state to retain information over long sequences.

With $[\mathbf{h}_{t-1}, \mathbf{x}_t]$ the concatenation of the previous state and the input:
$$\mathbf{f}_t = \sigma(W_f[\mathbf{h}_{t-1}, \mathbf{x}_t] + \mathbf{b}_f), \quad \mathbf{i}_t = \sigma(W_i[\mathbf{h}_{t-1}, \mathbf{x}_t] + \mathbf{b}_i), \quad \mathbf{o}_t = \sigma(W_o[\mathbf{h}_{t-1}, \mathbf{x}_t] + \mathbf{b}_o)$$
$$\tilde{\mathbf{c}}_t = \tanh(W_c[\mathbf{h}_{t-1}, \mathbf{x}_t] + \mathbf{b}_c)$$
$$\mathbf{c}_t = \mathbf{f}_t \odot \mathbf{c}_{t-1} + \mathbf{i}_t \odot \tilde{\mathbf{c}}_t, \qquad \mathbf{h}_t = \mathbf{o}_t \odot \tanh(\mathbf{c}_t)$$

**Elements**
- Cell state $\mathbf{c}_t$: long-term memory.
- Hidden state $\mathbf{h}_t$: output at step $t$.
- Forget gate $\mathbf{f}_t$: what to erase.
- Input gate $\mathbf{i}_t$: what to write.
- Output gate $\mathbf{o}_t$: what to expose.

**Properties**
- The additive update of $\mathbf{c}_t$ lets gradients flow over many steps, limiting the [[Vanishing Gradient]].
