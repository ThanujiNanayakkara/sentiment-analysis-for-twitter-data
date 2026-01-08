# sentiment-analysis-for-twitter-data
Sentiment Analysis for Twitter Data

# Twitter Sentiment Analysis using SVM
This project implements an end-to-end sentiment analysis system for Twitter data, classifying tweets as positive or negative using a Support Vector Machine (SVM).

## Overview
- Built as part of an MSc Natural Language Processing coursework
- Focuses on feature engineering, model optimisation, and error analysis
- Emphasises robustness to noisy, real-world social media text

## Dataset
- Twitter sentiment dataset (`sentiment-dataset.tsv`)
- External sentiment lexicons (positive & negative word lists)

## Approach
- Text preprocessing: token normalisation, note word handling, lemmatisation, punctuation handling
- Feature engineering:
  - Bag-of-words and TF-IDF representations
  - Word and character n-grams
  - Sentiment lexicon features
- Model:
  - Support Vector Machine (scikit-learn)
  - Class-weight balancing
  - Hyperparameter tuning (C parameter)
- Evaluation:
  - 10-fold cross-validation
  - Precision, recall, F1-score, accuracy
  - Confusion matrix and qualitative error analysis

## Results
- Baseline F1-score: ~0.83
- Final optimised model F1-score: ~0.89
- Improvements achieved through TF-IDF, n-grams, lexicon features, and chi-square feature selection

## Files
- `notebooks/` – Jupyter notebooks with full implementation
- `analysis/` – Error analysis and failure case inspection
- `report/` – Coursework report explaining methodology and results

## Notes
This project was completed individually. GenAI tools were **not used for coding**, only for conceptual guidance where permitted by the coursework.

## Technologies
Python, scikit-learn, NLP, SVM, TF-IDF

