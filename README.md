# Twitter-Sentiment-Analysis
Twitter Sentiment Analysis with Neural Networks

Hate speech is unfortunately a common occurrence on the Internet. Often social media sites like Facebook and Twitter face the problem of identifying and censoring problematic posts while weighing the right to freedom of speech. The importance of detecting and moderating hate speech is evident from the strong connection between hate speech and actual hate crimes. Sites like Twitter and Facebook have been seeking to actively combat hate speech. Despite these reasons, NLP research on hate speech has been very limited, primarily due to the lack of a general definition of hate speech, an analysis of its demographic influences, and an investigation of the most effective features.

Here, I have used different deep neural network models to effectively classify offensive comments.

# Data: 
Kaggle - (https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis)
Train.csv - Labelled dataset of 31,962 tweets. Csv file with each line storing:
1.	Tweet id
2.	Tweet sentence
3.	label '1' denotes the tweet is offensive and label '0' denotes the tweet is not offensive 
Test.csv – Each row of test data contains:
1.	Tweet id
2.	Tweet text with each tweet in a new line.

# Conclusion :
Among the Sequential, CNN and LSTM models i used, CNN performs better as we saw that False Negative Rate is very low which means model is able to classify maximum number of offensive comments accurately that will help app to delete such comments more effectively.

