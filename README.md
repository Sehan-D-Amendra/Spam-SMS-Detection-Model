# SMS Spam Detection

### Project Overview

This project implements a machine learning pipeline to classify SMS messages as either spam or legitimate (ham). Using natural language processing techniques and various classification algorithms, the system achieves high accuracy in identifying unwanted messages.

**Features:**
Text Preprocessing: Converts text to lowercase, removes punctuation, tokenizes words, removes stopwords, and applies lemmatization

**Feature Extraction:** Transforms text data into numerical features using TF-IDF vectorization
Model Training: Implements and compares multiple classification algorithms:

- Naive Bayes
- Random Forest
- Logistic Regression
- Support Vector Machine (SVM)

**Model Evaluation:** Analyzes performance using accuracy, precision, recall, and F1-score
**Visualization:** Creates word clouds and distribution plots to explore message patterns
**Hyperparameter Tuning:** Optimizes model parameters for best performance
**Deployable Model:** Saves the trained model for easy integration into applications

## Dataset
The project uses the SMS Spam Collection dataset, which contains 5,572 SMS messages labeled as either "ham" (legitimate) or "spam". The dataset is highly imbalanced with approximately 13.4% spam messages and 86.6% ham messages.

## Requirements
1. text
2. pandas
3. numpy
4. matplotlib
5. seaborn
6. scikit-learn
7. nltk
8. wordcloud
9. joblib
    
## Implementation Details
### Data Preprocessing
- Conversion to lowercase
- Punctuation removal
- Tokenization
- Stopword removal
- Lemmatization

## Feature Engineering
The system converts text data into numerical features using TF-IDF (Term Frequency-Inverse Document Frequency) vectorization with a maximum of 5,000 features.


SVM with a linear kernel achieved the best performance with 98.5% accuracy.



