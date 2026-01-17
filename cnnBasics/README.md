CNN From Scratch – Step by Step in NumPy

This is a learning-based implementation of how a Convolutional Neural Network (CNN) works internally — built step by step using only NumPy.

Instead of using deep learning libraries, each operation is coded manually to clearly understand what happens inside a CNN.

What This Notebook Covers:

Each Jupyter cell builds one part of a CNN pipeline-

1. Convolution

   Apply a 3×3 kernel on an image

   Slide the kernel and compute feature maps

2. Stride

   Move the kernel with step size > 1

   Reduce output size

3. Padding

   Add zeros around the image

   Control output dimensions

4. ReLU Activation

   Replace negative values with 0

   Add non-linearity

5. Pooling (Max Pooling)

   Downsample feature maps

   Keep strongest features

6. Flattening

   Convert 2D feature maps into 1D vector

   Prepare for fully connected layers

How to Run:

    Clone the repo
  
    Open the notebook in Jupyter or VS Code
  
    Run cells one by one to see each CNN step

Output:

    You will see-

      -Feature maps after convolution

      -Effects of stride and padding

      -Changes after ReLU and pooling

-Final flattened vector

-Each step is printed and visualized to make learning easier.

Goal of This Project:

Learn what happens inside libraries like TensorFlow and PyTorch. 
