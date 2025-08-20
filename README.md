# PyTorch-ResNet18-CIFAR10

This repository contains a PyTorch implementation of the ResNet-18 architecture from scratch for image classification on the CIFAR-10 dataset. The entire pipeline, from data loading to model training and evaluation, is demonstrated in a single Jupyter Notebook.

## 📝 Overview

The project aims to provide a clear and understandable implementation of a residual network (ResNet), a foundational architecture in deep learning for computer vision. The code is structured to be educational and easy to follow.

### Key Features:
* **ResNet-18 Architecture**: The model is built from scratch using basic PyTorch modules, including the `BasicBlock` for residual connections.
* **CIFAR-10 Dataset**: The model is trained and evaluated on the popular CIFAR-10 image dataset.
* **Complete Training Pipeline**: Includes data loading, transformations, a full training loop with validation, and final testing.
* **Performance Visualization**: The training and validation metrics (loss and accuracy) are plotted using `matplotlib` to visualize the learning process.

## 📈 Model Performance

After training for 10 epochs, the model achieves the following performance on the test set:

* **Final Test Accuracy**: **79.47%**

🏗️ Code Structure
The Jupyter Notebook py_resnet.ipynb is organized as follows:

Imports: All necessary libraries are imported.

Data Loading & Preprocessing: The CIFAR-10 dataset is loaded, transformed, and split into training, validation, and test sets. DataLoader is used to create data batches.

Model Definition:

BasicBlock: Defines a single residual block with two convolutional layers and a shortcut connection.

ResNet18: Constructs the full ResNet-18 model using BasicBlock modules.

Training:

The model, loss function (CrossEntropyLoss), and optimizer (Adam) are defined.

A training_loop function handles the training and evaluation for each epoch.

Evaluation & Visualization:

A plot_metrics function visualizes the loss and accuracy curves.

The final model is evaluated on the test set to determine its accuracy.

![Training and Validation Metrics](py_resnet.ipynb#cell-432316b1)

