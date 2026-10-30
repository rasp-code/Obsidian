---
created: 2026-09-11
updated: 2026-10-28
---
The **Transformer** is a [[Neural Network]] architecture for sequences based entirely on attention, without recurrence or convolution.

**Self-attention**
$$\mathrm{Attention}(Q, K, V) = \mathrm{softmax}\!\left(\frac{QK^\top}{\sqrt{d_k}}\right) V$$
- $Q = XW_Q$, $K = XW_K$, $V = XW_V$: queries, keys and values computed from the input tokens $X$.
- The output for each token is an average of all values, weighted by query–key similarity (see [[Dot Product]], [[SoftMax]]).
- Multi-head attention: several attentions in parallel, concatenated.

**Block**
- Multi-head attention, then a feedforward [[MLP]], each with a residual connection and a normalization.
- Positional encodings are added to the input, since attention ignores order.

**Properties**
- Computed in parallel over the sequence; every token attends directly to every other.
- Cost $O(n^2)$ in the sequence length $n$.
