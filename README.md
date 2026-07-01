# Swiggy Review Sentiment Analysis using NLP Pipeline
NLP pipeline to preprocess and analyse Swiggy app customer reviews
for sentiment classification using Python and NLTK.

## Dataset
swiggy_appReviews.csv — contains customer review text (content column)

## Tools & Libraries
Python, NLTK, Pandas, NumPy, Re (Regex), Jupyter Notebook

## NLP Pipeline Steps
1. Data loading and inspection using Pandas
2. Duplicate removal and shape check
3. Text cleaning using Regex (remove non-alphabetic characters)
4. Normalization (lowercase conversion)
5. Stop word removal using NLTK stopwords
6. Tokenization using word_tokenize
7. POS tagging using averaged perceptron tagger
8. Lemmatization using WordNetLemmatizer with POS context

## How to Run
Open swiggy_sentiment_analysis.ipynb in Jupyter Notebook
Place swiggy_appReviews.csv in the same directory
