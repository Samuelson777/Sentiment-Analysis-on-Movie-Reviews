# Sentiment Analysis on Movie Reviews

## Overview
This project implements a sentiment analysis tool that classifies movie reviews as positive or negative using machine learning techniques. The tool utilizes the IMDb Movie Reviews dataset to train a Multinomial Naive Bayes classifier.

## Table of Contents
- [Technologies](#technologies)
- [Dataset](#dataset)
- [Evaluation Results](#evaluation-results)
- [Future Work](#future-work)
- [Conclusion](#conclusion)

## Technologies
- Python
- Pandas
- Scikit-learn
- NLTK
- Jupyter Notebook (optional)

## Dataset
The dataset used for this project is the IMDb Movie Reviews dataset, which can be downloaded from [here](https://ai.stanford.edu/~amaas/data/sentiment/). The dataset contains positive and negative movie reviews stored in separate text files.

## Evaluation Results

| Metric    | Class 0 (Negative) | Class 1 (Positive) | Accuracy | Macro Average | Weighted Average |
| --------- | ------------------ | ------------------ | -------- | ------------- | ---------------- | 
| Precision | 0.85               | 0.88               | null     | 0.86          | 0.86             | 
| Recall    | 0.88               | 0.85               | null     | 0.86          | 0.86             | 
| F1-Score  | 0.87               | 0.86               | 0.86     | 0.86          | 0.86             | 
| Support   | 2485               | 2515               | 5000     | 5000          | 5000             | 
|           |                    |                    |          |               |                  | 

## Confusion Matrix

[[2193  292]
 [ 388 2127]]
 
## Future Work

- Experiment with advanced models (e.g., SVM, BERT).
- Implement hyperparameter tuning for improved accuracy.
- Develop a web application using Flask or Django for broader accessibility.

## Conclusion

In this project, we developed a sentiment analysis tool that classifies movie reviews as positive or negative using the IMDb dataset. We successfully processed raw text data, applied TF-IDF for feature extraction, and trained a Multinomial Naive Bayes classifier, achieving satisfactory performance metrics. The project included a user-friendly command-line interface for real-time predictions. Future enhancements could involve using advanced models, hyperparameter tuning, and deploying a web application to broaden accessibility and application scope.
