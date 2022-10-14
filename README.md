# NLP_Project 
#### submitted by:
- Supadit Wanotayapitak
- Niphon Chalen

In this project of Natural Language Processing , we chose to distinguish
NFL and NCAA posts from Reddit. There are three jupyter notebooks:
- requesting posts data
- EDA
- modeling and evaluation

Model: Pipeline and Gridsearch
- Transformer: 
  - CountVectorizer
  - TfidfVectorizer
- Estimators: 
  - Logistic Regression
  - Multinomial NaiveBayes
  - RandomForest
- Hyperparameter: 
  - max_fearues: range(100,1001,100)
  - stop_words: [None, English]
  - n_grams: Unigram, Bigram, Trigram
