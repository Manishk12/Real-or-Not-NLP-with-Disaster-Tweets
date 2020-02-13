# Real-or-Not-NLP-with-Disaster-Tweets
Predict which Tweets are about real disasters and which ones are not?
# Dataset
-The datasets contains a set of tweets which have been divided into a training and a test set. The training set contains a target column identifying whether the tweet pertains to a real disasteror not.\
-Our job is to create a ML model to predict whether the test set tweets belong to a disaster or not, in the form of 1 or 0. This is a     classic case of a Binary Classification problem.
# Understanding the Evaluation Metric
for this particluar problem, our submissions will be evaluated using F1 between the predicted and expected answers.\
-The F score, also called the F1 score or F measure, is a measure of a test’s accuracy.\
-The F score is defined as the weighted harmonic mean of the test’s precision and recall.\
-Precision, also called the positive predictive value, is the proportion of positive results that truly are positive.\
-Recall, also called sensitivity, is the ability of a test to correctly identify positive results to get the true positive rate.\
-The F score reaches the best value, meaning perfect precision and recall, at a value of 1. The worst F score, which means lowest precision and lowest recall, would be a value of 0.

# Table of Contents of My Code
1. Importing the necessary libraries
2. Reading the datasets
3. Basic EDA
4. Text data processing
5. Transforming tokens to vector
6. Buiding a Text Classification model.
