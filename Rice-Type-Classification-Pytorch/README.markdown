# Rice Type Classification with PyTorch

This repository contains a machine learning project that classifies rice types using tabular data with PyTorch. The model leverages morphological features of rice grains to predict their class (e.g., 0 or 1) based on a dataset sourced from Kaggle.

## Overview

The project implements a neural network using PyTorch to perform binary classification on the "Rice Type Classification" dataset. It includes data preprocessing, model training, and evaluation, with visualizations of training and validation metrics.

## Features

- Downloads and preprocesses the rice classification dataset from Kaggle.
- Builds and trains a PyTorch model on GPU (if available).
- Visualizes training and validation loss and accuracy over epochs.
- Provides a prediction function for new input data.

## Dataset

The dataset is obtained from Kaggle: Rice Type Classification. It contains features such as Area, MajorAxisLength, MinorAxisLength, Eccentricity, ConvexArea, EquivDiameter, Extent, Perimeter, Roundness, and AspectRation, with a binary Class label.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/rice-type-classification.git
   cd rice-type-classification
   ```
2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Set up Kaggle credentials:
   - Install `opendatasets` and provide your Kaggle username and API key when prompted to download the dataset.

## Usage

1. Run the Jupyter notebook `Rice_type_classification(Tabular_Pytorch).ipynb` in a compatible environment (e.g., Google Colab or local Jupyter).
2. Follow the cells to download the dataset, preprocess the data, train the model, and make predictions.
3. Adjust hyperparameters or input data as needed for your use case.

## Results

- The model achieves high accuracy on the validation set after training.
- Example prediction: For normalized input features, the model predicts a class (e.g., 0) with reasonable confidence.

## Dependencies

See `requirements.txt` for a list of required Python packages.

## Acknowledgments

- Dataset provided by Kaggle.
- Built using PyTorch and other open-source libraries.