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

