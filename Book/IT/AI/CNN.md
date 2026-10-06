---
created: 2026-09-11
updated: 2026-10-06
---
(EPITA, DNN - Part 1)

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

(EPITA, DNN - Part 2)
Feature Map (e.g. RGB = 3 feature maps)
Pooling (e.g. Max pooling, average pooling)

Famous Dataset
ImageNet
MNSIT
CIFAR

Famous CNN architectures:
AlexNet (first net to beat human on ImageNet)
ResNet (Res for residual, skip connexions)
VGG (very simple architecture)
MobileNet (conceived by Google for mobile phone, small)
EfficientNet (based on MobileNet, small yet powerful, version B0 to B7)

Beyond Image Classification
- -> Localisation (e.g. where's the dog on the image)
- -> Object Detection
	- -> Semantic Segmentation (all dogs)
	- -> Instance Segmentation (each dog)

Localisation
- Single object per Image
- Predict coordinates of a bounding box `(x, y, w, h)`
- Evaluate via **Intersection over Union (IoU)**
Localisation + Classification
- multi-task learning: 1 backbone with 2 heads (classification for the class with softmax, and regression for the 4 box coordinates)
- Total loss is weighted over the two outputs
Object Detection
- We don't know in advance the number of objects in the image.
- Object detection relies on _object proposal_ and _object classification_
	- Object proposal : find regions of interest (RoIs) in the image
	- Object classification : classify the object in these regions
- Two main families
	- single-stage : A grid in the image where each cell is a proposal (SSD, YOLO, RetinaNet)
	- tow-stage : Region proposal then classification (Faster-RCNN)
	- **single stage is faster than two stage !**
	- single stage examples
		- YOLO
			- After ImageNet pretraining, the whole network is trained end-to-end
			- The loss is a weighted sum of different regressions
		- RetinaNet
			- Multiple scales through a _Feature Pyramid Network_
			- Focal loss to manage imbalance between background and real objects
- Measure performance: mAP (mean Average Precision, at given IoU thresholds)
- Anchor-based vs Anchor-free
	- anchor-based: predefined boxes to adjust
	- anchor-free: predict center points

"VIT c'est le transformer à retenir en vision", le prof

Pour les UNet de nos jour on va pas faire conv + deconv mais conv + resize
