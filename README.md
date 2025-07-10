Key Features:
 Text cleaning and preprocessing (stopword removal, stemming)

 Feature extraction using TF-IDF Vectorizer

 Classification model using Logistic Regression

 Evaluation using confusion matrix and classification report

 Workflow Steps:
 Load Data
Loads tweet sentiment dataset from:


https://raw.githubusercontent.com/dD2405/Twitter_Sentiment_Analysis/master/train.csv
Keeps only label and tweet columns.

 Text Preprocessing
Converts to lowercase

Removes special characters and numbers

Removes stopwords using nltk

Applies stemming using PorterStemmer

 Feature Extraction
Uses TfidfVectorizer to convert text into numeric features.

Model Building
Splits data into training and testing sets

Trains a Logistic Regression classifier

Predicts sentiment on test data

 Evaluation
Classification Report (Precision, Recall, F1)

Confusion Matrix visualized with seaborn heatmap

