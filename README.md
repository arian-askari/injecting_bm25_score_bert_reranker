# Injecting the BM25 Score as Text Into BERT-Based Re-rankers
Arian Askari, Amin Abolghasemi, Gabriella Pasi, Wessel Kraaij and Suzan Verberne. *Injecting the BM25 Score as Text Improves BERT-Based Re-rankers*. ECIR 2023 (full paper).

## Quick run notebook

To quickly train a cross-encoder_BM25CAT re-ranker in a knowledge distillation (KD) setup, you could use the implementation below.

[train_cross-encoder_kd_BM25CAT](https://colab.research.google.com/drive/1mzWJ3vBciCYpjce75rHirLwUYL_4nTdS?usp=sharing) [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1mzWJ3vBciCYpjce75rHirLwUYL_4nTdS?usp=sharing) 

Please note that in the full paper version, we do not use KD. Using KD increase the effectiveness and more information about that is available on the following repository [ms-marco-MiniLM-L-12-v3](https://github.com/arian-askari/ms-marco-MiniLM-L-12-v3/), in which we also proivde run files of training KD-MiniLM_BM25CAT. 
