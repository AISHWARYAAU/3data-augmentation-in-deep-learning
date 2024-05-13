# Data Augmentation in Deep Learning

This project demonstrates the implementation of data augmentation techniques in deep learning using TensorFlow. Data augmentation is a common practice in training deep learning models to improve model generalization and robustness by artificially expanding the training dataset with modified versions of the original data.

## Installation

To run the code in this project, you'll need to install the required dependencies. You can install them using pip:

```bash
pip install git+https://github.com/tensorflow/docs
pip install tensorflow tensorflow_datasets
```

## Overview

The project includes:

1. **Single Image Augmentation**: Demonstrates various image augmentation techniques such as flipping, grayscale conversion, saturation adjustment, brightness adjustment, rotation, and cropping on a single image.

2. **Dataset Augmentation and Model Training**: Illustrates how to apply data augmentation to a dataset and train a deep learning model using augmented data. We use the MNIST dataset for this demonstration.

## Usage

1. **Single Image Augmentation**: Run the provided Python script `single_image_augmentation.py` to visualize different augmentation techniques on a sample image.

2. **Dataset Augmentation and Model Training**: Execute the Python script `dataset_augmentation_and_training.py` to augment the MNIST dataset and train a neural network model with and without augmentation.

## Repository Structure

```
.
├── single_image_augmentation.py      # Script for single image augmentation
├── dataset_augmentation_and_training.py # Script for dataset augmentation and model training
└── README.md                         # This README file
```

## Contributions

Contributions to this project are welcome! If you have suggestions for improvement or new augmentation techniques to add, feel free to open an issue or submit a pull request.

