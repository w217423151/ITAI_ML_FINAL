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

Maria Jose Viveros Riquelme 

**Comparative Analysis of Model Validation and Ensemble Models**
My main contribution to this project focused on the comparative analysis of model validation and ensemble methods, a stage essential for transforming numerical outputs into meaningful analytical conclusions. Rather than participating in the initial model training phase, my role focused on reviewing, interpreting, and structurally comparing validation results, as well as evaluating ensemble strategies. This allowed the project to move from isolated metrics to a clearer understanding of which models performed best and why. Once the individual classifiers had been trained, I began by reviewing the performance of Logistic Regression, Decision Tree, Random Forest, XGBoost, K-Nearest Neighbors, and Support Vector Classifier under the same validation conditions. My analysis did not focus only on accuracy, but on the joint interpretation of accuracy, precision, recall, F1-score, and ROC-AUC. This approach enabled identification not only of which models achieved higher global performance, but also of how well they detected positive cases and controlled classification errors. A key part of my contribution was supporting a balanced interpretation of evaluation metrics. I emphasized that a high-accuracy model can still exhibit weaknesses in recall or precision, and that the F1-score and ROC-AUC offer a more stable perspective on performance. In addition, I contributed to interpreting ROC curves as a visual tool, helping connect theoretical definitions of model performance with their actual behavior across different decision thresholds.
Another essential component of my contribution was selecting the Top 3 models based on validation accuracy. This step was crucial because it defined which models would serve as the base learners for all ensemble methods. I supported this selection as a data-driven process that ensured the ensemble architecture was built only from the strongest and most reliable individual models. Once the Top 3 models were established, my primary analytical focus shifted to comparing ensemble strategies, particularly the Bayesian Ensemble and the Stacking Ensemble. I contributed to the interpretation of why the Bayesian Ensemble, despite its solid theoretical formulation, showed weaker empirical performance. In contrast, through comparative analysis, I identified the Stacking Ensemble as the strongest model, explaining its superiority in terms of its meta-learning structure and its ability to dynamically combine model predictions. Beyond numerical comparison, my contribution also involved the organization and communication of results, transforming tables and outputs into a coherent comparative narrative. Finally, my work integrated classroom learning, external research, and AI-assisted validation into a unified analytical framework, ensuring that the final modeling decisions were supported by both quantitative evidence and conceptual understanding.
