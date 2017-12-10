# NLP – Product Rating

## Objective:  
The objective of this repository is to create prediction on product ratings based on a text given from customer feedback.  Retailers often have a form where users can write reviews on products but many times retailers don’t have a star rating system.  This repository will be creating a model to predict the rating of product 1-5 stars with 5 being the highest.  

## How it works:
To create the model I will be training the model on Amazon reviews.  Amazon product reviews have a star rating system so that can be used as the target output prediction; however, the model weights which were trained can be used to provide a rating for other products that don’t have an Amazon style product rating system.  

## Method:
There are different methods for classifying text as a rating system.  

  ### Generative (Naive Bayes): 
  Learns by the joint probability distribution p(x,y) then by using Bayes is transformed to p(y/x) however you are not directly         computing p(y/x).  In this classifier for text analysis, there is an assumption that the words are independent of one another.  

  ### Discriminative(RNN): 
  Learns the conditional probability distribution p(y/x) "probability of y given x.  This type of model would read the data sequentially to try and figure out the difference in ratings based on examples.  
