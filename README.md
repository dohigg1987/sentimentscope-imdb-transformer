# SentimentScope: IMDB Sentiment Analysis with a Transformer Built from Scratch

**Author:** Dennis O'Higgins

This project trains a small GPT-style transformer, implemented from scratch in PyTorch, to classify IMDB movie reviews as positive or negative.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dohigg1987/sentimentscope-imdb-transformer/blob/main/sentimentscope_notebook.ipynb)

## Contents
- `sentimentscope_notebook.ipynb`: the notebook with all code (data loading, exploration, dataset, model, training, evaluation, inference interface, conclusion).
- The trained model checkpoint (`sentimentscope_checkpoint.pt`, 77.28% test accuracy) is supplied in the submission zip and is regenerated when the notebook is run.

## Running
Open the notebook in Google Colab with a GPU runtime and choose Run all. The IMDB dataset is downloaded automatically.
