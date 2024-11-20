<h1> Convolutional Neural Networks </h1>

This repository implements two APIs for building and training convolutional neural networks (CNNs): Sequential and Functional.

1. Sequential API: Binary Classification
The Sequential API is used to solve a binary classification problem: identifying whether faces in 64x64 RGB images are happy (smiling) or not.

Example Input:
<img src="images/sad_face.png" />
<figcaption>Sad face</figcaption>

Model Architecture: ZeroPadding2D -> Conv2D -> BatchNormalization -> ReLU -> MaxPooling2D -> Flatten -> Dense

2. Functional API: Multi-Class Classification
The Functional API is designed for classifying hand gesture numbers (e.g., "1", "2", "3") from 64x64 RGB images.

Example Input:
<img src="images/two_sign.png" />
<figcaption>Sign two</figcaption>

Model Architecture: Conv2D -> ReLU -> MaxPooling2D -> Conv2D -> ReLU -> MaxPooling2D -> Flatten -> Dense
