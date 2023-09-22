# Injecting the BM25 Score as Text Into BERT-Based Re-rankers
Arian Askari, Amin Abolghasemi, Gabriella Pasi, Wessel Kraaij and Suzan Verberne. *Injecting the BM25 Score as Text Improves BERT-Based Re-rankers*. ECIR 2023 (full paper).

Please check out my recent github repository on a follow-up work on this idea, in that you could see example of injecting BM25 score for training BM25CAT models. Also, I provide BM25 scores in that repo: [https://github.com/arian-askari/ms-marco-MiniLM-L-12-v3/blob/main/train/train_ms-marco-MiniLM-L-12_v3_bm25.py](https://github.com/arian-askari/ms-marco-MiniLM-L-12-v3/blob/main/train/train_ms-marco-MiniLM-L-12_v3_bm25.py#L546)


## Quick run notebook

To quickly train a cross-encoder_BM25CAT re-ranker in a knowledge distillation setup, you could use the implementation below:

[train_cross-encoder_kd_BM25CAT](https://colab.research.google.com/drive/1mzWJ3vBciCYpjce75rHirLwUYL_4nTdS?usp=sharing) [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1mzWJ3vBciCYpjce75rHirLwUYL_4nTdS?usp=sharing) 
