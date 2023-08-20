### About
An NLP project that compares different approaches to document representation and classification. 
The techniques used include Topic-modeling, Tf-Idf, doc2vec, word2vec, FastText, SVM, and CNN

### Data
The 20 Newsgroups data set is a collection of approximately 20,000 newsgroup documents, 
partitioned evenly across 20 different newsgroups. 
The 20 newsgroups collection has become a popular data set for experiments in 
text applications of machine learning techniques, such as text classification and text clustering.
The data has been sourced from http://qwone.com/~jason/20Newsgroups/

### Steps
1. Conducted Exploratory Data Analysis (EDA) and subsequently performed Data Cleaning.
  The cleaning process encompassed handling outliers, refining the text corpus, eliminating non-ASCII characters, 
  excluding stop words, applying stemming and lemmatization, and generating unigrams and bigrams.
2. Employed various feature engineering techniques,
  including TF-IDF Vectorizer, word2vec, Count Vectorizer, to tokenize the data for model compatibility.
3. Employed machine learning methodologies for the categorization of documents into 20 distinct news groups.
  Multiple classifiers were employed in training, such as the Multinomial Naïve Bayes Model, Logistic Regression,
  Stochastic Gradient Descent Classifier, k Nearest Neighbors, and Neural Networks.
4. Evaluated the model's performance for various combinations of the classifiers and vectorizers
   using various metrics like accuracy, precision, recall, and F-score to identify the optimal fit.

