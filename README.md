# Injecting the BM25 Score as Text Into BERT-Based Re-rankers
Arian Askari, Amin Abolghasemi, Gabriella Pasi, Wessel Kraaij and Suzan Verberne. *Injecting the BM25 Score as Text Improves BERT-Based Re-rankers*. ECIR 2023 (full paper).

## Quick run notebook

To quickly train a cross-encoder_BM25CAT re-ranker in a knowledge distillation (KD) setup, you could use the implementation below. All of files including the BM25 injection scores and the dataset will be automatically downloaded thorough Notebook. You only need to run all cells.

[train_cross-encoder_kd_BM25CAT](https://colab.research.google.com/drive/1mzWJ3vBciCYpjce75rHirLwUYL_4nTdS?usp=sharing) [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1mzWJ3vBciCYpjce75rHirLwUYL_4nTdS?usp=sharing) 

## Relevant notebook to the extension of this work
Please check out the following repository for training cross-encoder_DPRCAT ["Injecting the Score of the First-stage Retriever as Text Improves BERT-Based Re-rankers"](https://github.com/arian-askari/ms-marco-MiniLM-L-12-v3/), in which all of the scores json file are available and we also proivde run files in TREC format.
