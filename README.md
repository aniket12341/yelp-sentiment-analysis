# Yelp Review Sentiment Analysis

This project performs 3-class sentiment analysis on the Yelp Review dataset.

## Project Overview
The original Yelp dataset contains 5 review classes based on star ratings.  
In this project, the labels are converted into 3 sentiment classes:

- Negative
- Neutral
- Positive

## Models Used
- Logistic Regression
- Linear SVM
- BERT
- DistilBERT
- DeBERTa + LoRA
- RoBERTa + LoRA

## Workflow
1. Import libraries
2. Load and explore Yelp Review dataset
3. Preprocess text data
4. Create TF-IDF features
5. Train classical ML models
6. Fine-tune transformer models
7. Evaluate using:
   - Accuracy
   - Classification report
   - Confusion matrix
   - ROC curves

## Dataset
- Yelp Review Full dataset from Hugging Face

## File
- `Yelp_sentiment` - complete notebook implementation

## Author
Aniket
