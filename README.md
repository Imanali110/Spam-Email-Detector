A machine learning-based spam email detection system developed as part of the "Intro to AI" course at Air University. This project leverages Natural Language Processing (NLP) techniques and multiple classifiers to efficiently distinguish spam from legitimate emails.

🚀 Features
✅ Preprocessing & Text Cleaning

Removes special characters, numbers, and punctuation
Converts text to lowercase
Applies stemming using NLTK’s PorterStemmer
✅ Feature Extraction using Bag-of-Words

Uses CountVectorizer to transform email text into numerical features
Selects the top 4,000 most frequent words
✅ Machine Learning Models

Trains and evaluates Random Forest, Decision Tree, and Multinomial Naïve Bayes classifiers
Compares accuracy, confusion matrices, and classification reports
✅ Real-time Spam Detection

Implements a function to classify new emails as Spam or Ham
Uses the trained Naïve Bayes model for prediction
✅ Data Visualization

Generates word frequency distributions for spam emails
Creates confusion matrix heatmaps for model evaluation
📊 Model Performance
Model	Accuracy (%)
Random Forest	XX.XX%
Decision Tree	XX.XX%
Naïve Bayes	XX.XX%
(Replace "XX.XX" with actual accuracy values)

🛠️ Technologies Used
Python
NLTK (Text preprocessing, stopwords, stemming)
Scikit-learn (Machine learning models, feature extraction)
Matplotlib & Seaborn (Data visualization)
Pandas & NumPy (Data handling)

Dataset used: https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset
