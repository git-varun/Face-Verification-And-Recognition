---

# Face Verification and Recognition

Welcome to the Face Verification and Recognition repository. This project uses deep learning models and a Triplet loss function to calculate the error and image encodings for face verification and recognition.

## Overview

The goal of this project is to develop an algorithm that can verify a person's identity using a face image. The project uses a deep learning model to generate encodings of face images, and a Triplet loss function to calculate the error between these encodings. The model can then compare the encodings of two face images to verify whether they are of the same person.

## Key Components

- **Main.ipynb**: This Jupyter notebook contains the main code for the project. It includes the steps for loading and preprocessing the data, creating and training the model, and making predictions.

- **fr_utils.py**: This Python file contains utility functions used in the project.

- **inception_blocks_v2.py**: This Python file contains the code for the Inception model used in the project.

- **nn4.small2.v7.h5**: This file contains the pre-trained weights for the model.

- **datasets**: This directory contains the datasets used in the project.

- **images**: This directory contains the images used in the project.

- **weights**: This directory contains the weights for the model.

## Getting Started

To get started with this project, clone the repository and install the required Python packages. You can then run the `Main.ipynb` notebook to train the model and make predictions.

Please note that this project is a work in progress, and the model's predictions should not be used for actual face verification without further testing and validation.

---
