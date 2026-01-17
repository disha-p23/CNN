Mini CNN from Scratch (NumPy + OpenCV)

This file demonstrates a simple Convolutional Neural Network (CNN) built from scratch in Python using NumPy and OpenCV, without deep learning frameworks like TensorFlow or PyTorch.

It shows how convolution, ReLU, pooling, and dense layers work, step by step, with visualizations for each stage.

Overview:

This project is structured into multiple cells/sections to demonstrate CNN operations:

1. Conv1 → ReLU → Pooling

   Apply the first convolution layer with only one filter

   Vertical edge detector

   Apply ReLU activation to remove negative values.

   Apply max pooling to downsample the feature maps.

   Visualize how each operation changes the image.

2. Conv1 → Conv2 → Conv3

   Apply additional convolution layers to the pooled feature maps from the previous layer.

   Observe how feature maps evolve and capture more complex patterns.


3. Effect of Pooling

    Compare feature maps with and without pooling.

    Understand how pooling reduces spatial dimensions and computation while preserving important features.

4. Multiple Filters in a Convolution Layer

    Apply multiple filters to each feature map.

    Demonstrates how CNNs capture diverse features in a single layer.

    Flatten all feature maps to feed into a fully connected (dense) layer.

    Dense Layer and Prediction

 5. Flattened feature maps → dense layer (2 neurons: apple / not apple).

    Apply softmax to convert outputs into probabilities.

    Make final class prediction.

Notes:

The CNN in this repository is from scratch, using only NumPy and OpenCV.

Dense layers are untrained, so predictions are random unless you implement training.

Visualizations are provided for Conv → ReLU → Pooling steps to see how features evolve.


Running the Code

Make sure apple.jpg is in the same folder as the notebook (cnnTest.ipynb)
