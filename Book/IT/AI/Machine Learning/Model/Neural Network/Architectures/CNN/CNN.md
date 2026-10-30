---
created: 2026-09-11
updated: 2026-10-28
---
A **convolutional neural network (CNN)** is a [[Neural Network]] that uses convolutions to process grid-structured data, mainly images.

**Layers**
- [[Convolutional Layer]]: extracts local features with learned filters.
- [[Batch Normalization]]: normalizes activations.
- [[Pooling Layer]]: reduces the spatial size.
- [[Dense Layer]]: produces the final prediction.

**Properties**
- Local connectivity: each neuron sees a small region of the input (receptive field).
- Weight sharing: the same filter is applied everywhere, so far fewer parameters than an [[MLP]].
- Convolution is translation-equivariant.
