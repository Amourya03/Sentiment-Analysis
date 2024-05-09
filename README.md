# Amazon Reviews Sentiment Analysis

## Overview
This project aims to analyze the sentiment of Amazon reviews using two different techniques: VADER (Valence Aware Dictionary and sEntiment Reasoner) and the Roberta Pretrained model from Hugging Face. The sentiment analysis is performed on a dataset of Amazon reviews to classify the sentiment of each review as positive, negative, or neutral.

## Techniques Used
1. **VADER (Valence Aware Dictionary and sEntiment Reasoner):** VADER is a lexicon and rule-based sentiment analysis tool specifically designed for analyzing sentiments in text data. It provides a polarity score for each sentence or text based on a predefined list of words and rules.

2. **Roberta Pretrained Model from Hugging Face:** The Roberta model is a deep learning-based language model pretrained on a large corpus of text data. It utilizes the transformer architecture and is fine-tuned on a specific downstream task, in this case, sentiment analysis of Amazon reviews.

## Dataset
The dataset used for this project consists of Amazon reviews across various product categories. Each review in the dataset is labeled with its corresponding sentiment (positive, negative, or neutral).

## Usage
1. **VADER:**
   - Input: Amazon review dataset in CSV format.
   - Output: Sentiment analysis results with polarity scores.

2. **Roberta Pretrained Model:**
   - Input: Amazon review dataset in CSV format.
   - Output: Predicted sentiment labels for each review.

## Requirements
- Python 3.x
- Libraries: pandas, nltk, transformers (for Roberta model), torch (for Roberta model)

 
