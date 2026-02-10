# 💬 Aspect-based Sentiment Analysis for Vietnamese

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=flat-square&logo=python)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Model](https://img.shields.io/badge/Model-PhoBERT-yellow?style=flat-square)

A comprehensive system for **Aspect-based Sentiment Analysis (ABSA)** on Vietnamese text. This project identifies specific aspect categories (e.g., Food, Service, Price) within reviews and classifies the sentiment polarity (Positive, Negative, Neutral) for each aspect.

## 🚀 Key Features

* **Multi-task Learning:** Jointly learns two tasks: Aspect Category Detection (ACD) and Sentiment Polarity Classification (SPC) using a unified architecture.
* **PhoBERT Backbone:** Utilizes pre-trained **PhoBERT** embeddings for state-of-the-art Vietnamese language understanding.
* **Data Augmentation:** Implemented **Back-translation** (Vietnamese ↔ English) to enrich the training dataset and improve model generalization on unseen text.
