Project Made/Contributor = Ayush Mehra
(Guided by Krish Naik sir)

Problem Statement - Credit Card Fraud Detection.

Context -.
As we know frauds are happening more and more and credit cards companies should be able to recognize the transaction that was not made by the card owner and he should not be charged for the items he did not purchase.

This project will classify whether the transaction made by the user is illegal or not.
The algorithms used in this project is
1 - Isolation Forest Algorithm
2 - Local Outlier Factor(LOF) Algorithm
3 - Support Vector machine.
And will compare all of these.

What is Isolation Forest Algorithm?

The Isolation Forest algorithm isolates observations by randomly selecting a feature and then randomly selecting a split value between the maximum and minimum values of the selected feature. Therefore, an anomaly score can be calculated as the number of conditions required to separate a given observation.

What is Local Outlier Factor(LOF) Algorithm?

The LOF algorithm is an unsupervised outlier detection method that computes the local density deviation of a given data point with respect to its neighbors. It considers as outlier samples that have a substantially lower density than their neighbors.

What is Support Vector machine?

The objective of the support vector machine algorithm is to find a hyperplane in N-dimensional space(N — the number of features) that distinctly classify the data points.

Data Set - The data set is taken from https://www.kaggle.com/mlg-ulb/creditcardfraud.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions. Confusion matrix accuracy is not meaningful for unbalanced classification.

The project uses Python's inbuilt sklearn(sklearn.metrics, sklearn.ensemble, and sklearn.neighbors) library to built Isolation forest and Local Outline factor and then compares both of them.

We have classified and done a detailed data analysis of the data using Python’s inbuilt matplotlib and seaborn library for visualization purposes.

Final Result - 

Isolation forest has 99.74% more accurate than LOF of 99.65% and SVM of 70.09%.
Fraud cases detection in isolation forest is 27 % and in LOF it is just 2 %  and SVM it is 0 %.
To improve we can increase the sample size or some deep learning algorithms but that will increase the computational expense. 
Isolation Forest detected 73 errors versus Local Outlier Factor detecting 97 errors vs. SVM detecting 8516 errors

(The code is commented for better understanding)




