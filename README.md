# Loan-Approval-Prediction
There are 3 categorical columns and 10 numerical columns in dataset.
Firstly, I have done Data preprocessing. It involves checking missing values, outlier detection and checking distribution of each numericaal columns.
For categorical columns, One hot encoding is used. 
In Model fitting part, Multiple classification models like, Decision tree, Random Forest, XGBoost, Adaboost, Gradiant boost and Histogram Bossting classifier are used. I have used K fold cross validation For finding best model for each above mentioned algorithm. 
After that, using best models predicition on test set is done by Averaging predicition from each models. 
Accuracy on test set is: 98.36%
F1 score is: 0.987
