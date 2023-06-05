## Click Through Rates : 

The aim of this project is to find out if a user will click an adveristement or not. 

The data set has been taken from Kaggle (link is inside the notebook). This is a binary classification problem.

The data contains categorical and numerical features. The categorical data has been transformed using OneHotEncoder and the numerical features has been scaled using StandardScalar.

For binary classification one may use several Classification algorithms. In this case, it is found that the classes are not linearly seperable. So, Logistic approach was not used. Instead nearest neighbor and ensemble techniques has been used for this problem. 
KNN, SVM, Decision Tree and Random Forest classifiers has been used. 

The metrics - the confusion matrix, accuracy, precision, recall, f1 score, roc curve, auc score were studied closely and it was observed that Random forest performs the best. To find the best parameters, hyperparameter tunings are also done.