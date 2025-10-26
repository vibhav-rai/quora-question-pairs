# Quora Question Pairs – Duplicate Question Detection

Built a **BERT-based NLP model** to identify whether two Quora questions have the same meaning.

### Objective

Classify question pairs as *duplicate* or *non-duplicate* using transformer-based embeddings.

### Tech Stack

`Python`, `PyTorch`, `Hugging Face Transformers`, `Datasets`, `scikit-learn`

### Concepts Implemented

* Text preprocessing & tokenization with **BERT tokenizer**
* Fine-tuning **`bert-base-uncased`** for sentence-pair classification
* Training via **Hugging Face Trainer** (with evaluation per epoch)
* Metrics: Accuracy, F1

### Results

| Metric    |   Score   |
| :-------- | :-------: |
| Accuracy  | **89.3%** |
| F1-score  | **86.1%** |
