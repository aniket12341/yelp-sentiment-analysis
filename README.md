# Sentiment Classification at Scale: Traditional ML vs Transformers on Real Reviews

This project performs sentiment analysis on Yelp reviews using both traditional machine learning models and transformer-based deep learning models.

## Academic Details
- **Student Name and SRN:** Aniket Mane - 23096043
- **Programme:** MSc Data Science
- **Module:** 7PAM2002-0206-2025 - Final project report

## Project Objective
The aim of this project is to classify Yelp customer reviews into sentiment categories by comparing the performance of classical machine learning methods with modern transformer models.

## Dataset
The dataset used in this project is the Yelp Review dataset.  
The original review ratings are converted into sentiment classes for classification.

### Sentiment Labels
- Negative
- Neutral
- Positive

## Models Used
### Machine Learning Models
- Logistic Regression
- Linear SVM

### Transformer Models
- BERT
- DistilBERT
- DeBERTa + LoRA
- RoBERTa + LoRA

## Project Workflow
1. Import libraries
2. Load and inspect dataset
3. Preprocess review text
4. Convert labels into sentiment classes
5. Feature extraction using TF-IDF
6. Train machine learning models
7. Fine-tune transformer models
8. Evaluate model performance
9. Compare results

## Evaluation Metrics
The models are evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC Curve

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Hugging Face Transformers
- PyTorch
- PEFT / LoRA

## File in Repository
- `Yelp_sentiment.ipynb` 
- `requirements.txt`
- `README.md`
- `.gitignore`

## Results
The project compares the effectiveness of traditional machine learning techniques and transformer-based architectures for sentiment classification on Yelp reviews.

## How to Run

### 1. Clone the repository
Download or clone this repository to your local machine:

```bash
git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name
```
### 2. Install the required dependencies using:

```bash
   pip install -r requirements.txt
```
### 3. Launch Jupyter Notebook or JupyterLab.
### 4. Open the notebook file Yelp_sentiment.ipynb.
### 5. Run the cells in sequence from top to bottom.
### 6. The notebook will guide you through dataset loading, preprocessing, model training, and evaluation.
### 7. Review the final outputs, performance metrics, and visualisations for model comparison.

## Author
Aniket

## Note
This project was created for academic and learning purposes.
