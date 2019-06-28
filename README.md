# Amazon Product Review Analysis

By Beverly Huang

### Preprocessing data
* Stemming & Lemmatization
* Removing Stopwords
* Removing words appearing less than 3 times
* Vectorizing words with TF-IDF

### Classification model buidling
* Three Machine Learning Models are used for prediction
* Grid search is applied to increase the models performance
* Three models are evaluated on precision, recall, F-1 score and ROC-AUC
* In this problem, we want to minimize false positives (misclassification of a dissatisfied customer into satisfied), which is to maximize the precision of our prediction
* Overall logistic regression performs best with the highest accuracy and precision

### LDA model interpretation
* By implementing LDA model, you can easily extract the top topics in those reviews
* By looking at key words of each topics, you can quickly understand customers' overall feedback on products and understand the market trend
