# MNIST Handwritten Digit Recognition CNN

A Convolutional Neural Network (CNN) built using TensorFlow/Keras to recognize handwritten digits from the MNIST dataset.  
The model achieves high accuracy (~98-99%) and can predict both MNIST test images and custom handwritten digits.

---

## Features

- Trains on MNIST dataset (60,000 images)  
- Two convolutional layers with ReLU activation and max pooling  
- Fully connected layer followed by softmax output  
- Achieves ~98-99% accuracy on test data  
- Can predict custom handwritten digits


## Model Architecture

1. Conv2D (32 filters, 3x3) + ReLU
2. MaxPooling2D (2x2)
3. Conv2D (64 filters, 3x3) + ReLU
4. MaxPooling2D (2x2)
5. Flatten
6. Dense (128 units, ReLU)
7. Dense (10 units, Softmax)


## Installation

1. Install required packages:

       pip install tensorflow matplotlib numpy

## Usage

1. Open `mnist_cnn.ipynb` in Jupyter Notebook
   
2. Run all cells to train the CNN or load a pre-trained model:
   
       from tensorflow.keras.models import load_model
       model = load_model("mnist_cnn.keras")
   
3. To test on your own handwritten digits:
   
   Just change the file name of the image by the one you have to test it.
   > Tip: Place your image in the same folder as the notebook (or provide the correct path) and change the file name to test different digits.
   
