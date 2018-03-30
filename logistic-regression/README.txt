To run code open up jupyter notebook. To run this code you need to have scikit-learn installed. 
There are two classes that are relevant to this assignment LogisticRegression and SimplifiedSMO. LogisticRegression
is an implementation of the logistic regression classifier and SimplifiedSMO is an implementation of SMO SVM as per the 
article given in class.

There is a KFoldCVLogit Function which implements grid search for the best eta and lambda for logistic function.
The function decisionBoundary plots the logit decision boundary. Plotted for both training and testing set.
ClassificationError = num classified wrong/total samples.
EffectOfC plots the effect of the regularization parameter C on SMO's output. Done for both training and testing data.