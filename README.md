# Sentiment Classification Amazon-review

<b> Final_Amazon_VideoGames_Reviews_NLP file contains all data cleaning and data preprocessing </b>

<ul><li>
In this project I have applied NLP techniques to classify sentiment of review. I went through all process of building a NLP engine which includes <b>data mining, data cleaning, feature engineering and building a model</b>. I have used three approaches to solve this problem.</li><br><li>
First I used all algorithms individually and explored their performance. Logistic Regression beat almost all algorithms by far distance.</li><br><li>
Then I created <b>voted classifier</b> which consists of <b>seven</b> different classifiers. It predicts review sentiments with confidence level but accuracy is not different from individual logistic algorithm. Only advantage is that it gives confidence based on voting of models.</li><br><li>
So then I created Deep Learning model which used Word Embedding and LSTM layers. Here I got <b>80%</b> accuracy but it was not that significantly different then previous models but you can increase accuracy of this model by adding more layers, neurons, epochs and data.</li>I have only trained model with 5 epochs.

<li>Conclusion:
For getting more accuracy you have to use deep learning models because in Machine Learning models, CoW(count of words) and TFIDF does not present much values, it basically predictes sentiment on count of words that are present in review. But that is still a good choice for low resources.<br>
</li></ul>

# Text-Generation

Key-Learing-Points: Web Scraping, Language Modelling, NLP, Deep Learning
