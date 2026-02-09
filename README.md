Telco Customer Churn Prediction
Objective
The objective of this project is to predict whether a customer will churn (Yes/No) using the Telco Customer Churn dataset. 
This task is modeled as a binary classification problem using supervised machine learning techniques.

Train / Validation Split
The dataset was split into 80% training data and 20% validation data using stratified sampling to maintain the original churn distribution.
A fixed random state was used to ensure reproducibility.

Evaluation Metric
Model performance was evaluated using accuracy. Confusion matrices were also reviewed to better understand prediction behavior.

Best Result
Logistic Regression achieved the highest accuracy on the validation set and was selected as the best-performing model.

Conclusion
This project presents a complete machine learning workflow for customer churn prediction, including preprocessing, exploratory analysis, model training, and evaluation. 
While ensemble-based models such as Random Forest and XGBoost were explored, 
Logistic Regression produced the highest accuracy on the validation set and was therefore chosen as the final model.
