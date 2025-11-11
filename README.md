# SentimentScope: A Transformer for IMDB Sentiment Analysis

This is a project from the Udacity [Your Nanodegree Name] Nanodegree. I built a transformer model from scratch using PyTorch to perform sentiment analysis on the IMDB movie review dataset.

**Final Test Accuracy: 76.61%**



---

## 📋 Project Overview

The goal was to build a complete transformer-based classifier, starting from raw text data and ending with a trained model. This involved:
* Loading and exploring the raw `.txt` files from the IMDB dataset.
* Creating a custom PyTorch `Dataset` and `DataLoader` to tokenize and batch the text.
* Building all the transformer components (AttentionHead, Blocks) from scratch.
* Customizing the final model (`DemoGPT`) for binary classification.
* Training the model and achieving over 75% accuracy on the test set.

## 🚀 Key Features

* **Transformer from Scratch:** All core components, including the self-attention mechanism and transformer blocks, were built using pure PyTorch.
* **Custom Data Pipeline:** Implemented a custom `Dataset` class to handle tokenization, padding, and truncation on the fly.
* **Classification Head:** Adapted the standard transformer architecture for a classification task by adding a mean pooling layer and a final linear head.
