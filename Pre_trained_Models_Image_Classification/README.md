# Pre-trained GoogLeNet for Image Classification

This project demonstrates image classification using the pre-trained **GoogLeNet** model from PyTorch on a custom dataset for **Bean Leaf Lesion Classification from Kaggle**.

🔗 Link to various PyTorch pre-trained models: [https://pytorch.org/vision/stable/models.html]

## Highlights

- Uses the **GoogLeNet** model pre-trained on ImageNet.
- Compares performance between:
  - **Frozen GoogLeNet** (only final fully connected layer trained).
  - **Fine-tuned GoogLeNet** (all layers trainable).
- Applied on **Bean Leaf Lesion** dataset for detecting plant diseases.
- Visualizations and training evaluation techniques included.

## Model Comparison: Frozen vs. Fine-tuned

### 1. Frozen Model (`requires_grad = False`)
- Only the final classification layer is updated.
- Pre-trained on ImageNet (general images like dogs, cars).
- **Drawback**: Cannot capture specific features like leaf lesions.
- **Performance**: ~50–60% accuracy due to poor domain adaptation.

### 2. Fine-tuned Model (`requires_grad = True`)
- Entire model is trainable.
- Leverages pre-trained weights but adapts all layers to the specific task.
- **Performance**: 80–94% accuracy with faster convergence and better feature learning.

## Setup

1. Install dependencies using the `requirements.txt` file.
2. Launch the Jupyter Notebook:
```bash
jupyter notebook Pre_trained_Models_Image_Classification.ipynb
```

## Requirements

* Python 3.8+
* PyTorch
* torchvision
* matplotlib
* pandas
* numpy
* Pillow
* scikit-learn
* opendatasets

## License

This project is for educational and research purposes only.
