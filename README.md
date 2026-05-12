# LLM-or-Not-Kaggle-pkarlos

## Overview

This project fine-tunes the TinyBERT transformer model for binary text classification using PyTorch and Hugging Face Transformers.
Run this like a reguler .ipynb file in a CUDA environment.

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

---

# Project Structure

```text
project-folder/
│
├── pkarlos2-tinybert.ipynb
├── train.csv
├── test.csv
├── prediction.csv   # Generated after inference
└── README.md
```

---

# Author

Peter Karlos
Freshman Computer Engineering Student at the University of Illinois Urbana-Champaign.
