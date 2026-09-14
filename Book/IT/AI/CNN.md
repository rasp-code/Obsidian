---
created: 2026-09-11
updated: 2026-09-11
---
CNN = Convolutional Neural Network

Convolutional layer -> 3 key points:
- Translation Equivariance
- Receptive field
- Parameter sharing

As you go through the layers:
- the spatial dimension decreases
- the semantic dimension increases

Hyperparameters:
- Spatial parameters (kernel dimensions)
- Stride (it's not called the step)
- Padding

Kernel Shape -> (F, F, Ci, Co):
- F * F = kernel size
- Ci input channels
- Co output channels
number of parameters = (F * F * Ci + 1) * Co
Activations or Feature maps shape:
- Input (Wi,Hi,Ci)
- Output (Wo,Ho,Co)

Some famous CNNs:
- AlexNet (first one to beat humans on the ImageNet dataset)
- VGG-16 (first "simple" CNN to work so well)
- ResNet (uses residual connexions, uses batch normalisation)
- Inception (Google, inception score)
- EfficientNet (currently the best, 2026)