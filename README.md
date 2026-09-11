# True-and-Fake-News-NLP-GloVe-LSTM-
NLP fake news classifier using GloVe word embeddings and an LSTM model to distinguish real vs. fake news articles based on text content.

# True and Fake News Detection — NLP (GloVe & LSTM)

## Overview
This project builds a text classification model to distinguish between
real and fake news articles using Natural Language Processing techniques.
The goal is to automatically flag misinformation based on the textual
content of news headlines/articles, using GloVe word embeddings and an
LSTM-based deep learning model.

## Dataset
True and Fake news datasets — labeled news articles categorized as
genuine or fabricated, used to train a binary text classifier.

## Approach
- Text preprocessing: tokenization, stop-word removal, stemming/lemmatization,
  and text cleaning/normalization
- Used pre-trained GloVe word embeddings to represent text numerically
- Built and trained an LSTM (Long Short-Term Memory) model to classify
  articles as true or fake
- Evaluated model predictions against labeled ground truth

## Evaluation
Achieved 99% accuracy on the test set, with a weighted F1-score of 0.99.

| Class | Precision | Recall | F1-score |
|-------|-----------|--------|----------|
| Fake  | 0.99      | 0.99   | 0.99     |
| True  | 0.98      | 0.99   | 0.98     |

## Tools & Libraries
Python, TensorFlow/Keras, GloVe Embeddings, Pandas, NLTK / Scikit-learn

## Key Takeaway
Combining pre-trained word embeddings (GloVe) with a sequence model (LSTM)
captures contextual meaning in text better than simple word-count-based
approaches, which is key for detecting subtle linguistic patterns in
fake news.
