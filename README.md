# Finance-Capstone


Problem Statement
* Finance Industry is the biggest consumer of Data Scientists. It faces constant attack by fraudsters, who try to trick the system. Correctly identifying fraudulent transactions is often compared with finding needle in a haystack because of the low event rate. 
* It is important that credit card companies are able to recognize fraudulent credit card transactions so that the customers are not charged for items that they did not purchase.

The datasets contain transactions made by credit cards in September 2013 by European cardholders. This dataset represents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.
  
It contains only numerical input variables which are the result of a PCA transformation. 
Features V1, V2, ... V28 are the principal components obtained with PCA. 
The only features which have not been transformed with PCA are 'Time' and 'Amount'
 
# Project Task: Week 1

**Exploratory Data Analysis (EDA):**

1. Perform an EDA on the Dataset.
2. Check the class count for each class. It’s a class Imbalance problem.
3. Use techniques like undersampling or oversampling before running Naïve Bayes, Logistic Regression or SVM.
  a. Oversampling or undersampling can be used to tackle the class imbalance problem
  b. Oversampling increases the prior probability of imbalanced class and in case of other classifiers, error gets multiplied as the low-proportionate class is mimicked multiple times.
4. Following are the matrices for evaluating the model performance: Precision, Recall, F1-Score, AUC-ROC curve. Use F1-Score as the evaluation criteria for this project.

# Project Task: Week 2

**Modeling Techniques:**

Try out models like Naive Bayes, Logistic Regression or SVM. Find out which one performs the best
Use different Tree-based classifiers like Random Forest and XGBoost. 
1. Remember Tree-based classifiers work on two ideologies: Bagging or Boosting
2. Tree-based classifiers have fine-tuning parameters which takes care of the imbalanced class. Random-Forest and XGBboost.
Compare the results of 1 with 2 and check if there is any incremental gain.

# Project Task: Week 3

**Applying ANN:**

Use ANN (Artificial Neural Network) to identify fradulent and non-fradulent.
1. Fine-tune number of layers
2. Number of Neurons in each layers
3. Experiment in batch-size
4. Experiment with number of epochs. Check the observations in loss and accuracy
5. Play with different Learning Rate variants of Gradient Descent like Adam, SGD, RMS-prop. Find out which activation performs best for this use case and why?
6. Check Confusion Matrix, Precision, Recall and F1-Score

7. Try out Dropout for ANN. How is it performed? Compare model performance with the traditional ML based prediction models from above. 
8. Find the best setting of neural net that can be best classified as fraudulent and non-fraudulent transactions. Use techniques like Grid Search, Cross-Validation and Random search.
9. Implement anomaly detection algorithms.
 
# Project Task: Week 4

Inference and Observations:
1. Visualize the scores for Fraudulent and Non-Fraudulent transactions.
2. Find out the threshold value for marking or reporting a transaction as fraudulent in your anomaly detection system.
3. Can this score be used as an engineered feature in the models developed previously? Are there any incremental gains in F1-Score? Why or Why not?
4. Be as creative as possible in finding other interesting insights.

