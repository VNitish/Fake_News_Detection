# Fake News Detection using Text Classification

This repository contains a Python script for detecting fake news using a text classification model. The model is built using TensorFlow and Keras libraries and is trained to classify news articles as either "True" or "False" based on their content.

## Table of Contents

- [Introduction](#introduction)
- [Setup](#setup)
- [Usage](#usage)
- [Results](#results)
- [License](#license)

## Introduction

Fake news detection is a crucial task in today's information-rich world. This script aims to classify news articles using a text classification model. The model is trained on a labeled dataset of news articles, where each article is labeled as "True" or "False."

The script uses a combination of techniques, including tokenization, padding, and embeddings, to preprocess the text data. It then builds a convolutional neural network (CNN) and a long short-term memory (LSTM) layer for classification. The model is trained and evaluated using accuracy as the metric.



## Usage

1. Prepare your dataset: You need a labeled dataset containing news articles and their corresponding labels ("True" or "False"). The dataset should be in CSV format with columns for title, text, and label.

2. Update the `news.csv` file with your dataset.

3. Run the script:
   ```
   python fake_news_detection.py
   ```

   This will train the model using the provided dataset and display training progress and results.

## Results

After training, the model's performance is evaluated on a separate test dataset. The accuracy metric is used to assess the model's ability to classify news articles as either real or fake.

The script also includes a sample text that can be used to test the trained model's ability to classify a news article as "True" or "False."
