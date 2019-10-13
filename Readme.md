The complete computation on the dataset was done on Google Colab.
Since correlational analysis was not used, the following methods for feature selection have been tried :-
**-Principal Component Analysis
**-Recursive Feature Elimination

Note for every method of feature selection I have iterated for a range of features and selected the number for which the error was minimum.
Following combinations were tried.
**PCA and Linear Regression 
PCA and SVR
PCA and Random Forest.
RFE and Linear Regression
RFE and Random Forest.**

Final submission is PCA and Linear Regression with **features = 12**. Which gave the lowest errors while testing over the split dataset.


