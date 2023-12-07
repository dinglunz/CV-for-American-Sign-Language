# Sign Language Recognition with Convolutional Neural Networks

## Overview

This repository contains a Python implementation of a Convolutional Neural Network (CNN) for recognizing sign language gestures using PyTorch. The model is trained on the American Sign Language (ASL) alphabet dataset.

## Requirements

- PyTorch
- torchvision
- matplotlib
- scikit-learn
- seaborn

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/dinglunz/CV-for-American-Sign-Language.git
   cd CV-for-American-Sign-Language

2. Download the ASL alphabet dataset and extract it into the project root directory.

    ```bash
    https://www.kaggle.com/datasets/grassknoted/asl-alphabet

3. Install the required dependencies:

    ```bash
    pip install -r requirements.txt

4. Run the Jupyter Notebook script.

    ```bash
    asl.ipynb

5. Explore the results:

- Learning curves (loss and accuracy) will be displayed in two subplots.
- A confusion matrix heatmap will be shown, illustrating the model's performance on different classes in the test set

## Results

The training script outputs learning curves, including losses and accuracies, and evaluates the model on a separate test set. The confusion matrix provides insights into the model's performance on individual classes.