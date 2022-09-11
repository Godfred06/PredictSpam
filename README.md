# PredictSpam

#Assignment 
Using predictive modelling to predict whether or not an email is a spam
Words in the spam email were tokenized and vectorized using the CountVectorizer
Extra features such as the length of the email, the number of non characters, and the number of digits were added as extra features to be used for the vectorization
Logistic Regression was used to fit the data with a regularization parameter set to 100
An AUC score of 0.99 shows that the model is a good fit and will do great at predicting whether or not an email is a spam
