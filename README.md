# Sentiment Analysis using Pre-trained BERT Model

This project performs **sentiment analysis** on text data using a **pre-trained BERT model** (`nlptown/bert-base-multilingual-uncased-sentiment`) from Hugging Face.

## Overview
The notebook `SentimentAnalysis.ipynb` uses a fine-tuned BERT model to predict the sentiment of text reviews on a 5-point scale.  
It categorizes the final output into:
- **Positive** (4–5 stars)
- **Neutral** (3 stars)
- **Negative** (1–2 stars)

## Features
- Load and preprocess text data from a CSV file (`reviews.csv`)
- Apply a Hugging Face transformer model for sentiment prediction
- Map numerical predictions to sentiment classes
- Output confidence scores for predictions

## Technologies Used
- Python
- Jupyter Notebook
- Hugging Face Transformers
- PyTorch
- pandas
- scikit-learn
