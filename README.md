#  Fake News Prediction 

--> <i> <b> DATASET : </b> </i> 

This dataset is taken from the https://www.kaggle.com/c/fake-news/data?select=train.csv

<i> About the Dataset : </i>

id:unique id for a news article

title: the title of a news article

author: author of the news article

text: the text of the article; could be incomplete

label: a label that marks whether the news article is real or fake

--> <i> <b> METHODOLOGY : </b> </i> 

The libraries used to implement this project are:
<i>
  
● SKLEARN

● NLTK

● NUMPY

● PANDAS

● REGULAR EXPRESSION(Re)
</i>

0 and 1 are used to predict whether the news is fake or not in the following way:

● 0 --> The News is Real

● 1 --> The News is Fake

Algorithm used to implement thsi proeject is <b> <i> Logistic Regression. </i> </b>

The prgram then divides the dataset into training and testing samples in <b> <i> 80:20 </i> </b> ratio randomly using <b> <i> train_test_split() </i> </b> function available in <b> <i> sklearn </i> </b> module.

Accuracy score is then calculated by comparing with the correct results of the training dataset.

--> <i> <b> OUTPUT : </b> </i> 

The resultant output of the project is:

<img width="394" alt="Screenshot 2022-09-04 at 2 46 11 PM" src="https://user-images.githubusercontent.com/71970250/188306438-4fcb837e-028a-4a50-bad5-bf82ae82f7e0.png">
