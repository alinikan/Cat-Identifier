# Deep L-Layer Neural Network for Image Classification

## Description
This project implements a deep L-layer neural network to classify images as either "cat" or "non-cat". The core logic of the neural network, including forward and backward propagation, is encapsulated in utility functions that make it easy to initialize, train, and evaluate the model.

## Table of Contents
- [Installation](#installation)
- [Dataset](#dataset)
- [Implementation Details](#implementation-details)
- [Usage](#usage)
- [Contributors](#contributors)

## Installation

### Prerequisites
- Python 3.x
- Jupyter Notebook

### Libraries Used
- numpy
- matplotlib
- h5py
- PIL (Pillow)
- scipy

To install the required libraries, run:
```bash
pip install numpy matplotlib h5py Pillow scipy
```

## Dataset
The dataset used is the "Cat vs non-Cat" dataset. It consists of:
- A training set of images labeled as cat (1) or non-cat (0).
- A test set of images labeled as cat or non-cat.
- Each image is of shape (num_px, num_px, 3) where 3 stands for the RGB channels.

## Implementation Details
The neural network is implemented as a deep L-layer model, with the flexibility to define as many layers as needed. The utility functions allow for the modular construction of the neural network, making it easy to tweak and optimize. Key functions include:

- Initialization of parameters
- Forward and backward propagation
- Computation of cost
- Parameter update using gradient descent
- Prediction based on learned parameters

The accompanying Jupyter notebook, `Neural_Network_Project.ipynb`, provides a step-by-step walkthrough of loading the dataset, exploring it, training the model, and evaluating its performance.

## Usage
1. Clone the GitHub repository.
2. Install the necessary libraries as mentioned in the [Installation](#installation) section.
3. Open the `Neural_Network_Project.ipynb` notebook in Jupyter Notebook.
4. Run the cells in sequence to train and evaluate the model.
5. Optional: Modify the network architecture or hyperparameters to optimize performance.

## Contributors
- Ali Nikan
- Sina Niyaki
