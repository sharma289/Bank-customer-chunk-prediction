# Bank-customer-chunk-prediction
The goal of this project is to evaluate the use of machine learning algorithms in predicting whether customers are likely to churn in the future based on account information.
An accurate model would allow BankCo to focus resources on incentivising potential churn customers to remain at the bank.
The following tasks were done:
1. Download Churn_Modelling.csv from kaggle and read the CSV file.
2. Identify independent and dependent features and encode categorical features.
3. Train-test split of data.
4. Balance the imbalanced data using under-sampling method.
5. Train the model using Logistic regression, SVM, Naive-Bayes classifier, Random forest classifier and XGBoost classifier and identify and model with best precision and recall.

XGBClassifier(gamma=0.01, learning_rate=0.2, max_depth=6, min_child_weight=5, n_estimators=20) was the best model which achieved 89% precision and 66% recall on test data.
