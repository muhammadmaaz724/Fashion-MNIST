# Fashion MNIST Model

This repository contains a neural network model built using TensorFlow and Keras to classify images from the Fashion MNIST dataset. The dataset consists of 60,000 training images and 10,000 testing images of fashion products across 10 categories.

## Dataset

The Fashion MNIST dataset is a collection of grayscale images of size 28x28 pixels representing fashion items in 10 categories:

1. T-shirt/top
2. Trouser
3. Pullover
4. Dress
5. Coat
6. Sandal
7. Shirt
8. Sneaker
9. Bag
10. Ankle boot

## Model Architecture

The model used in this project is a simple neural network with the following architecture:

- **Input Layer**: Flatten layer to reshape the 28x28 images into a 1D array of 784 pixels.
- **Hidden Layers**: 
  - Dense layer with 128 neurons and ReLU activation.
  - Dropout layer with a rate of 0.2 to prevent overfitting.
- **Output Layer**: Dense layer with 10 neurons and softmax activation for classification.

## Training

The model is compiled with the following configurations:
- **Loss Function**: Sparse Categorical Crossentropy
- **Optimizer**: Adam
- **Metrics**: Accuracy

The model is trained for 10 epochs with a batch size of 32.

## Usage

### Prerequisites

- Python 3.x
- TensorFlow
- Numpy
- Matplotlib

##Results

The model achieves an accuracy of approximately 87% on the test dataset.
