# Depression Detection using CNN

This project uses a Convolutional Neural Network (CNN) model to detect signs of depression in user-generated text. It combines multiple datasets from Kaggle, which have been preprocessed and merged for effective training.

## 📂 Project Structure

- `Depression detection CNN.ipynb`: Jupyter Notebook with data preprocessing, model training, and evaluation.
- The dataset used was compiled from multiple publicly available sources on Kaggle.

## 💡 Highlights

- Preprocessing steps that are done and not included in this project include emoji and noise removal, lowercasing, and tokenization.
- Model built using TensorFlow/Keras with embedding layers and 1D convolutions.
- Achieves strong performance on large-scale, multi-source text data.

## 📊 Dataset

The datasets were sourced from Kaggle and combined. Due to the large size (~500,000 entries), the dataset is not included in this repo.

You can download similar datasets here:
- [Kaggle Dataset 1](will provice source later)
- [Kaggle Dataset 2](will provice source later)

## 🔧 Requirements

- Python 3.7+
- TensorFlow
- scikit-learn
- pandas
- numpy
- matplotlib

Install dependencies:
```bash
pip install -r requirements.txt
