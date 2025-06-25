# Image Classification CNN - Animal Faces

This project performs image classification using a Convolutional Neural Network (CNN) on the [AFHQ - Animal Faces Dataset](https://www.kaggle.com/datasets/andrewmvd/animal-faces).

The dataset includes three animal classes: **cats**, **dogs**, and **wild animals**.

## 📁 Dataset

- Source: Kaggle ([Animal Faces Dataset](https://www.kaggle.com/datasets/andrewmvd/animal-faces))
- Structure:
  ```
  /animal-faces/afhq/
    ├── train/
    ├── val/
    └── test/
  ```

## 🧠 Model

- Framework: PyTorch
- Layers: Convolutional layers, ReLU activation, MaxPooling, Fully Connected (Linear) layers
- Optimizer: Adam
- Loss Function: CrossEntropyLoss

## 📊 Performance Metrics

- Accuracy
- Loss curves
- Classification Report

## 🚀 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/itsnaveenkroy/Pytorch-Works.git
   cd Pytorch-Works/Image-Classification-CNN
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:
   ```bash
   jupyter notebook Image_Classification_CNN.ipynb
   ```

4. Alternatively, convert to script and run:
   ```bash
   jupyter nbconvert --to script Image_Classification_CNN.ipynb
   python Image_Classification_CNN.py
   ```

## 🛠️ Dependencies

- PyTorch
- torchvision
- scikit-learn
- matplotlib
- pandas
- numpy
- opendatasets
- PIL

## 📌 Notes

- GPU acceleration is used if available.
- Dataset is automatically downloaded via `opendatasets`.

---
