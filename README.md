# Mental Health Sentiment Analysis

## Overview
This project focuses on sentiment analysis to assess mental health status based on textual data. Using advanced natural language processing (NLP) and machine learning, we aim to classify statements into seven categories: Normal, Depression, Suicidal, Anxiety, Stress, Bi-Polar, and Personality Disorder. This classification could aid mental health professionals in early identification and intervention.

## Installation
Ensure you have the following packages:

```bash
    pip install pandas numpy matplotlib seaborn nltk imbalanced-learn wordcloud scikit-learn xgboost
```

## Data Preprocessing
- **Text Cleaning**: Tokenization, stemming, and removal of stop words.
- **Vectorization**: *TF-IDF vectorization* to convert text into numerical format.
- **Oversampling**: Addressed data imbalance using *RandomOverSampler*.

## Modeling
**Algorithms**: Tested multiple models, including:
- **Logistic Regression**
- **Naive Bayes**
- **Decision Tree Classifier**
- **XGBoost Classifier**

**Evaluation**: Models are evaluated using *accuracy*, *precision*, *recall*, *F1-score*, and *confusion matrix*.

**Results**: The best-performing model achieved an accuracy of approximately 81%. See the notebook for detailed metrics and model comparisons.

## Future Work
- Fine-tune models for improved accuracy.
- Explore additional NLP techniques for feature extraction.
- Expand to more mental health categories if more labeled data becomes available.
