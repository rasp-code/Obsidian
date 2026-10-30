---
created: 2026-10-23
updated: 2026-10-28
---
An **autoencoder** is a [[Neural Network]] trained to reconstruct its input through a lower-dimensional bottleneck, to learn a compact representation:

$$\mathbf{z} = g_\phi(\mathbf{x}), \qquad \hat{\mathbf{x}} = h_\psi(\mathbf{z}), \qquad \min_{\phi, \psi} \|\mathbf{x} - \hat{\mathbf{x}}\|^2$$

**Elements**
- Encoder $g_\phi$: input → latent code $\mathbf{z}$.
- Decoder $h_\psi$: latent code → reconstruction $\hat{\mathbf{x}}$.
- Bottleneck: $\dim \mathbf{z} < \dim \mathbf{x}$.

**Properties**
- It is unsupervised: the target is the input itself.
- A linear autoencoder trained with squared error spans the same subspace as [[PCA]].

**Comparison**
- The [[VAE]] makes it generative.
