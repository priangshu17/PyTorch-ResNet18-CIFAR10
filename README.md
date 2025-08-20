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

### Training History
The following plots show the model's loss and accuracy on the training, validation, and test sets over 10 epochs.

![Training and Validation Metrics](py_resnet.ipynb#cell-432316b1)

