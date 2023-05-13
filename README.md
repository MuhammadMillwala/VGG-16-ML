# Fruit Recognition using VGG16 CNN architecture

This project implements a Convolutional Neural Network (CNN) with the VGG16 architecture to classify images of fruits. The dataset used for training and testing is the [Fruits-360 dataset](https://www.kaggle.com/moltean/fruits), which contains images of 120 different types of fruits.

## Installation

To run the code, you need to install the following dependencies:

- Python 3.x
- PyTorch
- torchvision
- NumPy
- Pandas
- Matplotlib

You can install PyTorch and torchvision via pip or conda. For example, to install PyTorch and torchvision with pip, run:

```
pip install torch torchvision
```

## Usage

The project consists of the following files:

- `vgg_architecture.py`: defines the VGG16 architecture as a PyTorch module.

## Results

After training the model for 4 epochs, we achieved an accuracy of 96.4% on the test set.

## Acknowledgement

- This project was inspired by the paper **Very Deep Convolutional Networks for Large-Scale Image Recognition**
- The link for the paper is as follows: https://arxiv.org/abs/1409.1556.
