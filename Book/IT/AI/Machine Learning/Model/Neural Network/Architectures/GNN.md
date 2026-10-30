---
created: 2026-10-23
updated: 2026-10-28
---
A **graph neural network (GNN)** is a [[Neural Network]] that operates on graphs, learning representations of nodes, edges or whole graphs.

**Message passing** (one layer)
$$\mathbf{h}_v^{(l+1)} = \varphi\Big(\mathbf{h}_v^{(l)},\; \mathrm{AGG}\big(\{\mathbf{h}_u^{(l)} : u \in \mathcal{N}(v)\}\big)\Big)$$
- Each node aggregates the features of its neighbors $\mathcal{N}(v)$ (sum, mean or max), then updates its own.

**Properties**
- Invariant to the order of the nodes.
- After $L$ layers, a node's representation depends on its $L$-hop neighborhood.
