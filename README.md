# Image-Classification-using-Quantum-Machine-Learning
This repository contains the implementation of Quantum Neural Networks (QNNs) for classifying images from the Fashion MNIST dataset. We utilize TensorFlow Quantum and Cirq to build and train our quantum models.

Introduction

Quantum computing offers a new paradigm for solving computational problems. Quantum Neural Networks (QNNs) leverage the principles of quantum mechanics to perform computations that may be infeasible for classical computers. This project demonstrates how QNNs can be applied to classify images from the Fashion MNIST dataset using TensorFlow Quantum and Cirq.

Dataset

The Fashion MNIST dataset consists of 70,000 grayscale images in 10 categories. The images show individual articles of clothing at low resolution (28x28 pixels). The training set has 60,000 images and the test set has 10,000 images.

Quantum Circuit

The quantum circuit is constructed using Cirq and consists of parameterized quantum gates. These gates are trained to learn the features of the input data.

Classical Network

The classical network is built using TensorFlow and consists of fully connected layers. The outputs from the quantum circuit are used as inputs to the classical layers.

Training

The training process involves the following steps:

Preprocessing the Fashion MNIST dataset.

Encoding the images into quantum states.

Constructing the quantum circuit using Cirq.

Integrating the quantum circuit with TensorFlow Quantum.

Defining the loss function and optimizer.

Training the QNN model.

Results

The results of the QNN model on the Fashion MNIST dataset are compared with classical neural networks. The performance metrics and visualizations of the results are provided.

Accuracy of the model: 

![accuracy](https://github.com/user-attachments/assets/26b05093-671a-4bf3-b4c1-99f515ffeba2)

Contributing

Contributions are welcome! Please read the contributing guidelines for more information.

License

This project is licensed under the MIT License. See the LICENSE file for details.
