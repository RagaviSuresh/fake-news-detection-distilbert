# Fake News Detection using DistilBERT

## Overview

This project uses DistilBERT, a lightweight transformer model from Hugging Face, to classify news articles as **Fake** or **Real**. The model was trained on the FakeNewsNet dataset using PyTorch and achieved an accuracy of **91.74%**.

## Dataset

* FakeNewsNet Dataset
* News articles labeled as Fake or Real

## Technologies Used

* Python
* PyTorch
* Hugging Face Transformers
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Gradio

## Model

* DistilBERT (`distilbert-base-uncased`)
* Binary Classification (Fake vs Real)

## Results

* Accuracy: 91.74%
* Precision, Recall and F1-score evaluated using Scikit-learn
* Confusion Matrix visualization included

## Features

* Data preprocessing
* Dataset balancing
* DistilBERT fine-tuning
* News prediction function
* Interactive Gradio interface
* Model saving and loading

## How to Run

1. Install dependencies:

```bash
pip install -r requirements.txt
```

2. Open the notebook:

```bash
FakeNewsDetection_DistilBERT.ipynb
```

3. Run all cells.

## Author

Ragavi Suresh
