# Fashion-MNIST
👗 Fashion-MNIST Classification

A deep learning project using TensorFlow/Keras to classify clothing images from the Fashion-MNIST dataset.
The goal is to train a model that recognizes fashion items such as T-shirts, sneakers, and bags with high accuracy.

🧥 Fashion-MNIST Dataset

Fashion-MNIST is a dataset of Zalando’s article images—consisting of 60,000 training images and 10,000 test images. Each example is a 28×28 grayscale image, associated with a label from 10 fashion categories.

It is a drop-in replacement for MNIST (handwritten digits), but more challenging and realistic for computer vision tasks.

📂 Dataset Details

Images: 28x28 grayscale

Training set: 60,000 images

Test set: 10,000 images

Number of classes: 10

| Label | Description |
| ----- | ----------- |
| 0     | T-shirt/top |
| 1     | Trouser     |
| 2     | Pullover    |
| 3     | Dress       |
| 4     | Coat        |
| 5     | Sandal      |
| 6     | Shirt       |
| 7     | Sneaker     |
| 8     | Bag         |
| 9     | Ankle boot  |
🚀 Project Overview

This project demonstrates how to build and train a deep learning model using TensorFlow/Keras on Fashion-MNIST.

🔑 Key Steps

Data Preprocessing: Normalize pixel values to [0,1].

Model Architecture:

Flatten input layer (28×28 → 784).

Dense layer with 128 neurons, ReLU activation.

Output layer with 10 neurons, Softmax activation.

Training:

Optimizer: Adam

Loss: Sparse Categorical Crossentropy

Metric: Accuracy

Epochs: 10

Evaluation:

Achieves ~88–90% accuracy on test data.

# ✨ Author: Heba Hossam
