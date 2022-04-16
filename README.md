# Fake-News-Classifier

Data Source: https://www.kaggle.com/c/fake-news

This Notebook contains CLassification model to classify whether a news is fake or not. 
Two Models were used in the project:
- Multinomial Naive Bays 
- Passive Aggressive classifier 

Pre-processing techniques involved:
- Stemming & removal of stopwords
- converting text to bag of words 
- creating a new dataframe and feeding it to classification models.

Out of the Two models Passive Aggressive Classifier outperformed MultinomialNB 

Model Accuracy on Test: 0.946
Confusion matrix, without normalization
F1_score: 0.946
Precision: 0.9430008382229673 
 Recall:0.9336099585062241
