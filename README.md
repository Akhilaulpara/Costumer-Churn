**📉 Customer Churn Prediction**

This project focuses on predicting customer churn using machine learning techniques. The goal is to identify customers who are likely to discontinue a service based on their historical data and behavior patterns.

**🧠 Model Used**
A Random Forest Classifier from sklearn.ensemble was implemented to classify customers as churned or not churned.

**⚙️ Feature Engineering**
Removed irrelevant columns such as id and unnamed index columns.
Separated the dataset into independent features (X) and the target variable (churn).
Applied a train-test split to validate model performance.

**📊 Prediction and Evaluation**
Trained the model using model.fit(X_train, y_train).
Made predictions using model.predict(X_test).
Evaluated model performance using key metrics:
Accuracy
Precision
Recall
