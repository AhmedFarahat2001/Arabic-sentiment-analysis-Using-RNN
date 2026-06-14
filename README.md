# Arabic Sentiment Analysis using Simple RNN

This repository contains a Natural Language Processing (NLP) pipeline designed to classify the sentiment of Arabic text (e.g., tweets, product reviews) into **Positive** or **Negative** categories using a **Simple Recurrent Neural Network (SimpleRNN)** built with TensorFlow/Keras.

---

## 🚀 Project Overview

Arabic sentiment analysis faces unique challenges due to rich morphology, diverse local dialects, and complex orthography (such as diacritics and elongations). This project demonstrates how to address these linguistic obstacles using custom text preprocessing steps and a fundamental deep learning architecture (`SimpleRNN`) to capture sequential dependencies in Arabic sentences.

## 🛠️ Features

* **Arabic-Specific Text Preprocessing:**
    * Removal of punctuation, emojis, and Digits. 
    * Removal of Arabic stop words.
      
* **Tokenization & Padding:** Converts text sequences into standardized numerical sequences ready for deep learning models.
* **Sequential Modeling:** Implements a trainable Embedding layer paired with Keras `SimpleRNN`.

