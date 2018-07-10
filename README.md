# Sentiment-Analysis

The aim of this project is to find the model that best fits the [training data](https://github.com/KARTHEEKCIC/Sentiment-Analysis/blob/master/training.txt) and then classify the comments in the [testing data](https://github.com/KARTHEEKCIC/Sentiment-Analysis/blob/master/testdata.txt). I have used TF-IDF vectorizer to extract the training features. I tried with four classifiers which are listed below along with testing accuracy - 

 * Multinomial Naive Bayes - 96.61%
 * K Nearest Neighbours - 95.27%
 * Logistic Regression - 97.21%
 * Neural Network (1 hidden layer with 100 nodes) - 99.10-99.30%

Of the above four classifier, neural network(using keras sequential model) outperformed the other four models. The final predictions for the test data are [here](https://github.com/KARTHEEKCIC/Sentiment-Analysis/blob/master/predictions.txt).
