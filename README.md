Review Sentiment Analysis with BERT
Overview

This project uses BERT (Bidirectional Encoder Representations from Transformers) for sentiment analysis on IMDB reviews.
It classifies reviews as positive or negative after fine-tuning a pre-trained BERT model.

Dataset

IMDB dataset in .parquet format:

train-00000-of-00001.parquet

test-00000-of-00001.parquet

unsupervised-00000-of-00001.parquet

Each entry contains:

text → Review content

label → Sentiment (0 = negative, 1 = positive)

Steps

Load and clean dataset.

Tokenize text using bert-base-uncased.

Fine-tune BERT with HuggingFace Trainer.

Evaluate model with accuracy, precision, recall, F1-score.

Predict sentiment for new text.

Example Prediction
text = "The movie was amazing!"
Predicted label: positive

Results

(Add your actual accuracy and metrics after training here)

Repository Structure
Dataset/             # parquet dataset files
Review Sentiment Analysis.py           # training and prediction code
README.md            # project description
