# LLM-or-Not-Kaggle-pkarlos

## Overview

This project fine-tunes the TinyBERT transformer model for binary text classification using PyTorch and Hugging Face Transformers.

The notebook:

* Loads and preprocesses text data
* Tokenizes text using a BERT tokenizer
* Fine-tunes TinyBERT for classification
* Tracks training/validation performance
* Generates predictions for a test dataset
* Exports predictions to a CSV file

Model used:

* `huawei-noah/TinyBERT_General_4L_312D`

Libraries used:

* PyTorch
* Transformers (Hugging Face)
* Pandas
* Matplotlib
* scikit-learn
* tqdm

# Project Structure

```text
project-folder/
│
├── .git/
├── data/
│   ├── train.csv
│   └── test.csv
├── notebooks/
│   └── pkarlos2-tinybert.ipynb
├── outputs/
│   └── prediction.csv
└── README.md
```

# How to Run

Run this like you would any other .ipynb file.
This project works in a CUDA enabled environment for significant time reduction.
Expect the model to train in around 30 minutes (trained on Kaggle with NVIDIA T4 x2).

# Author

Peter Karlos
Computer Engineering Student at the University of Illinois Urbana-Champaign.

