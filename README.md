# ITAI_ML_FINAL
# JANICE UNDERWOOD 
# Training Multiple Machine Learning Models
To compare different types of algorithms, we trained several models:

# • Logistic Regression
A simple, interpretable model that acts as a good baseline.
A simple linear model often used for binary classification.
It tries to find the best line (or surface) that separates the two classes.
It works well for linearly separable data.
•	Pros: Simple and easy to understand; fast to training and easy to interpret.
•	Cons: Struggles with no linear dataset; it can overfit on high-dimensional data, ex: having many columns; it needs too much pre-processing.

Code Result: Training model: Logistic Regression
Accuracy:  0.849
Precision: 0.733
Recall:    0.611
F1 Score:  0.666
ROC–AUC:   0.908

# • Decision Tree Classifier
A non-linear model that splits data into branches based on feature conditions.
Captures non-linear decision patterns and provides clear decision rules.
•	Pros: Easy to interpret ; requires less data processing compared to other algorithms; can handle both numerical and categorical data, as well as missing values.
•	Cons: Can overfit if not tuned; single trees are not robust; sensitive to small change

Code Result: Training model: Decision Tree
Accuracy:  0.804
Precision: 0.605
Recall:    0.597
F1 Score:  0.601
ROC–AUC:   0.759

# • Random Forest Classifier
It reduces overfitting and usually performs better than a single tree.
An ensemble of many decision trees, offering better accuracy and stability.
•	Pros: Resistant to overfitting ; robust to noise, outliers , missing values;  helps identify which variables are most influential in the prediction.
•	Cons: Slower to train than logistic regression, requires more memory; training the model can be time-consuming specially with large dataset

Code Result: Training model: Random Forest
Accuracy:  0.837
Precision: 0.687
Recall:    0.624
F1 Score:  0.654
ROC–AUC:   0.888

# Kim Nguyen
K-Nearest Neighbors (KNN), Support Vector Classifier (SVC), and XGBoost are three popular machine learning models, each with unique strengths and weaknesses. KNN is a simple, instance-based method that makes predictions by comparing new data to its closest neighbors, but it can be slow and sensitive to irrelevant features. SVC focuses on finding the best separating boundary with maximum margin and performs well in high-dimensional spaces, though it can be slow to train and requires careful tuning of parameters. XGBoost is a powerful ensemble boosting algorithm known for its high accuracy and speed, especially on structured data, but it can be complex to tune and may overfit if not properly regularized. Together, these models represent a range from simple to highly sophisticated techniques used in modern machine learning.
# XGBoost
It builds tree one at a time, where each new tree reduces errors of previous trees. It also helps to prevent overfitting better than standard Gradient Boosting Machines. And it works well with non-linear data.

Accuracy:  0.826

Precision: 0.676

Recall:    0.582

F1 Score:  0.625

ROC–AUC:   0.878

# K-Nearest Neighbors Classifier
This model works well with small and low-dimensional dataset. It is very simple and easy to understand.

Accuracy:  0.804

Precision: 0.625

Recall:    0.536

F1 Score:  0.577

ROC–AUC:   0.819

# Support Vector Classifier (SVC)
This is effective for clean, well-separated datasets. It is suitable for datasets with many features. It makes decisions based on a small subset of important data points.

Accuracy:  0.754

Precision: 0.504

Recall:    0.830

F1 Score:  0.627

ROC–AUC:   0.849


