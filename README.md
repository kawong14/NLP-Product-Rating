# NLP – Product Rating

## Objective:  
The objective of this repository is to create prediction on product ratings based on a text given from customer feedback.  This repository will be creating a model to predict the rating of product 1-5 stars with 5 being the highest.  

## How it works:
To create the model I will be training the model on Amazon reviews.  Amazon product reviews have a star rating system so that can be used as the target output prediction.

## Method:
There are different methods for classifying text as a rating system.  

  ### Generative (Naive Bayes): 
  Learns by the joint probability distribution p(x,y) then by using Bayes is transformed to p(y/x) however you are not directly         computing p(y/x).  In this classifier for text analysis, there is an assumption that the words are independent of one another.  

  ### Discriminative(RNN): 
  Learns the conditional probability distribution p(y/x) "probability of y given x.  This type of model would read the data sequentially to try and figure out the difference in ratings based on examples.  In this experiment I tried a number of different models (CNN, Multi Size CNN, and a LSTM).  

## Results:
The LSTM performed the best.  I will continue writing the document in the month of December. 
