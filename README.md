# MNIST-Digit-Classification-with-Keras
This project demonstrates how to classify handwritten digits from the MNIST dataset using a simple neural network implemented in TensorFlow and Keras.

Here’s a concise README for your MNIST digit classification project, including the model parameters and techniques used:

## Features

- **Loads and normalizes MNIST data**
- **Neural Network Architecture:**
  - Input: Flatten layer for 28x28 images
  - Hidden Layers: Dense (128 units, ReLU), Dense (64 units, ReLU)
  - Output: Dense (10 units, Softmax)
- **Training Parameters:**
  - Loss: `sparse_categorical_crossentropy`
  - Optimizer: `adam`
  - Metrics: `accuracy`
  - Epochs: 10
  - Validation split: 20% of training data
- **Techniques Used:**
  - Data normalization (scaling pixel values to [0, - Multi-layer neural network (MLP)
  - Accuracy and validation monitoring
  - Visualization of accuracy over epochs
  - Test set prediction and evaluation

## Requirements

- Python 3.x
- TensorFlow
- matplotlib
- scikit-learn

Install with:
```bash
pip install tensorflow matplotlib scikit-learn
```

## Usage

1. Clone the repository and navigate into it.
2. Run the Python script or notebook.
3. View training results, accuracy curves, and test sample predictions.

Modify and extend as needed for your use case!
