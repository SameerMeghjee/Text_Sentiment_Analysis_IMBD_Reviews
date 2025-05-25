# Text_Sentiment_Analysis_IMBD_Reviews
This project demonstrates how to build a sentiment analysis model using the IMDB Movie Reviews dataset from Kaggle. The model classifies movie reviews as positive or negative using text preprocessing, TF-IDF features, and a Logistic Regression classifier.

# Project Steps
1. Text Preprocessing
-  Convert all text to lowercase
-  Remove HTML tags and special characters
-  Tokenize the text into words
-  Remove stopwords
-  Perform lemmatization to normalize words

2. Feature Engineering
-  Transform the cleaned text into numerical format using TF-IDF Vectorization
-  Maximum of 5000 features used for dimensionality control

3. Model Training
-  The dataset is split into training (80%) and testing (20%)
-  A Logistic Regression classifier is trained to predict sentiment

4. Model Evaluation
The model is evaluated using:
- Precision
- Recall
- F1-score

# Observations
- Logistic Regression performs well on this balanced dataset.
- Preprocessing significantly improves model accuracy.
- You can experiment with other models like Naive Bayes, SVM, or deep learning (e.g., LSTM or BERT) for even better performance.
- Adding more complex feature engineering or word embeddings (e.g., Word2Vec, GloVe) could improve generalization.
