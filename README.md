# Sentiment Analysis on Twitter Brand Mentions

In this project, sentiment analysis is carried out on brand mentions on Twitter. Utilizing a [Twitter Sentiment Analysis Dataset](https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis) from Kaggle, several preprocessing steps such as text cleaning, stopword removal, and conversion of data into TF-IDF (Term Frequency-Inverse Document Frequency) representation is carried out.

After the data has been prepocessed, a baseline is set using a Multinomial Naive Bayes classifier as it is a probabilistic classifier that works well for text data. Afterwards, a Logistic Regression model is trained to predict the sentiment of the same set of tweets used on the baseline classifier. The performance of the Logistic Regression model is then compared to the baseline performance.

## Accuracy achieved

The baseline Multinomial Naive Bayes classifier achieved an accuracy of 94.13%, while the Logistic Regression model achieved an accuracy of 90.79%.

<img src="https://github.com/jxne00/brand-mentions-sentiment/blob/main/assets/lr-confusionmatrix.png" alt="Confusion Matrix">
