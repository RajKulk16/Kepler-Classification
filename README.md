# Kepler-Classification

1. Why did you choose the particular algorithm?

-> Algorithms with trees are much more efficient than non-tree algorithms. Hence, following algorithms were selected - 
a. Random Forest
b. AdaBoost
c. XGBoost

AdaBoost is selected as the best algorithm for this project.

2. What are the different tuning methods used for the algorithm?

-> We can either use GridSearchCV or RandomizedSearchCV for hyperparameter tuning. In this project RandomizedSearchCV has been performed with following hyperparameters - 

a. Random Forest - n_estimators, criterion, max_depth, min_samples_split, min_samples_leaf, max_leaf_nodes
b. AdaBoost - base_estimator, n_estimators, learning_rate
c. XGBoost - learning_rate, max_depth, min_child_weight, gamma

3. Did you consider any other choice of algorithm?Why or why not?

-> 3 tree-based algorithms have been selected and worked upon for this project. Using non-tree based algorithms, like Logistic Regression, were considered but not used as final model as the efficiency when compared tree-based algorithms is not high. 

4. What is the accuracy?

-> Accuracy is a performance metric in machine learning in which it measures the number of correctly classified samples out of total samples.

5. What are the different types of metrics that can be used to evaluate the model?

-> There are several metrics but the metrics used in this project are - 
a. Accuracy Score
b. Precision
c. Recall
d. F1-Score
