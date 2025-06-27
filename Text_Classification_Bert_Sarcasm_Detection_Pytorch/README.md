# Sarcasm Detection using BERT and PyTorch

This project performs **text classification** to detect **sarcasm in news headlines** using the BERT transformer model with PyTorch.

**Model:** Pretrained BERT via HuggingFace Transformers  
**Dataset:** [News Headlines Dataset for Sarcasm Detection](https://www.kaggle.com/datasets/rmisra/news-headlines-dataset-for-sarcasm-detection)

## Features

- Uses BERT tokenizer and model (`bert-base-uncased`)
- Custom PyTorch Dataset and DataLoader
- Fine-tunes BERT on sarcasm classification
- Training and validation accuracy tracking
- Evaluation using accuracy score
- Visualization of training loss/accuracy over epochs

## Setup

1. Clone the repo.
2. Install dependencies using the `requirements.txt` file.
3. Run the Jupyter notebook.

```bash
jupyter notebook Text_Classification_Bert_Sarcasm_Detection_Pytorch.ipynb
````

## Requirements

* Python 3.8+
* PyTorch
* Transformers (HuggingFace)
* scikit-learn
* pandas, numpy, matplotlib
* opendatasets (for Kaggle dataset download)

## License

This project is for educational purposes only.



---