# Transfer-Learning-and-Data-Agmentation-on-Natural-Scene-Dataset
Implementing Transfer Learning and Data Augmentation using Base Model, VGG16 and ResNet50for image classification.

Given :
Train Images : 14k images classified into 6 categories
Validation Images : 3k images classified into 6 categories
Test Images : 7k images without any classification

Regularization:
Early Stopping, Batch Normalization and Dropout

Hierarchy:
Code

Result:

| Attempt | Base Model | VGG16 | ResNet50 |
| Original Dataset |  83.6% | - | - |
| Transfer Learning  |  - | 84.7% | 51.4% |
| Transfer Learning & Data Augmentation |  - | 83.2 | 44.4 |
