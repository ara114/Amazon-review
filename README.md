# Amazon-review

Tuesday 7th February 2023 - Monday 3 April 2023 
used essential text processing, representation, analysis, and categorization tools
a data set of text reviews and the corresponding ratings provided by the user. The ratings
score different outdoor and sports products from 1 (low rating) up to 5 (maximum rating).
This can be considered a multi-class classification problem where your classes are the scores provided
by the user {1,2,3,4,5}. The features are the text reviews.
Using ‘analytics’ skills to provide insights on the data provided and to propose
a categorization system that can automatically rate similar text reviews.
The original dataset consists of reviews and metadata from Amazon, including 142.8 million reviews
spanning May 1996 to July 2014. The original data includes reviews (ratings, text, helpfulness votes),
product metadata (descriptions, category information, price, brand, and image features), and links
(also viewed/also bought graphs).
Dataset source: http://jmcauley.ucsd.edu/data/amazon/links.html
You will be working on a modified subset related to Sports and Outdoors purchases. This data set
will only include the ‘Review Text” and the corresponding rating {1,2,3,4,5} provided by the user.
A .csv file as the training/test data sets. Use this data set to train
your models and optimize your model parameters

#conclusion 
The experiment is conducted on a training dataset that requires high running time. The models are trained on a
sample of the training dataset. This has negatively affected the prediction and decreased efficiency. Despite this
drawback, the SVM produced an accuracy of 0.67 and the simple RNN produced an accuracy of 0.62. The pre-
processing increased the model's efficiency as there were not any outliers in the dataset. The topic modeling has
clustered the reviews into 10 topics, out of which topic 7 has the highest review numbers and topic six has the
least number of reviews. The machine-learning models outperformed the deep-learning models when the
running time is considered. The accuracy is quite similar for all the models and only varies by a small
percentage.
