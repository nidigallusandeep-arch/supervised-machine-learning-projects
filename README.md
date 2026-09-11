# 🤖 Supervised Machine Learning Projects

This repository contains my practical implementation of **Supervised Machine Learning algorithms** using Python and Scikit-learn.

I worked on different **Classification, Regression, Data Preprocessing, and Ensemble Learning algorithms** using real-world-style datasets.

---

## 📚 Projects / Algorithms

| No. | Algorithm / Topic | Project |
|---:|---|---|
| 1 | Numerical Data Preprocessing | Numerical Data Preprocessing |
| 2 | MinMaxScaler & RobustScaler | Feature Scaling |
| 3 | KNN Regression | House Price Prediction |
| 4 | KNN Classification | Customer Purchase Prediction |
| 5 | Linear Regression | House Price Prediction |
| 6 | Logistic Regression | Loan Approval Prediction |
| 7 | Naive Bayes | Email Spam Detection |
| 8 | Decision Tree | Email Spam Classification |
| 9 | SVM | Loan Approval Prediction |
| 10 | AdaBoost | Customer Churn Prediction |
| 11 | Gradient Boosting | Customer Churn Prediction |
| 12 | XGBoost | Customer Churn Prediction |

---

# 🧠 Machine Learning Algorithms

## 1. Numerical Data Preprocessing

Data preprocessing is the first step in a Machine Learning project.

### Techniques Used

- Missing Value Handling
- Outlier Detection
- Data Cleaning
- Feature Transformation
- Feature Scaling

---

## 2. MinMaxScaler & RobustScaler

### MinMaxScaler

Scales numerical features into a fixed range, usually **0 to 1**.

### RobustScaler

Uses the **median and interquartile range (IQR)** and is more resistant to outliers.

---

## 3. KNN Regression

### Project: House Price Prediction

K-Nearest Neighbors Regression predicts a continuous numerical value based on nearby data points.

### Dataset Features

- Area_sqft
- Bedrooms
- Bathrooms
- Age_years
- Distance_to_City_km
- Parking
- House_Price

### Evaluation Metrics

- MAE
- MSE
- RMSE
- R² Score

---

## 4. KNN Classification

### Project: Customer Purchase Prediction

KNN Classification predicts the class of a new data point based on its nearest neighbors.

### Dataset Features

- Age
- Annual_Income
- Credit_Score
- Years_Employed
- Purchase_Count
- Website_Visits

### Target

`Will_Purchase`

- Yes
- No

### Evaluation

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## 5. Linear Regression

### Project: House Price Prediction

Linear Regression predicts a continuous target variable by learning a linear relationship between features and the target.

### Target

`House_Price`

### Evaluation Metrics

- MAE
- MSE
- RMSE
- R² Score

---

## 6. Logistic Regression

### Project: Loan Approval Prediction

Logistic Regression is used for classification problems. In this project, it predicts whether a loan application is approved or rejected.

### Dataset Features

- Age
- Annual_Income
- Credit_Score
- Employment_Years
- Loan_Amount
- Debt_to_Income_Ratio
- Existing_Loans
- Dependents

### Target

`Loan_Approved`

- Yes
- No

### Evaluation

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Confusion Matrix

---

## 7. Naive Bayes

### Project: Email Spam Detection

Naive Bayes is a probabilistic classification algorithm based on Bayes' theorem.

### Dataset Features

- Word_Frequency
- Link_Count
- Capital_Ratio
- Exclamation_Count
- Email_Length
- Attachment_Count
- Unknown_Sender

### Target

`Email_Type`

- Spam
- Not Spam

### Techniques

- Feature Selection
- Chi-Square Test
- Gaussian Naive Bayes

### Evaluation

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## 8. Decision Tree

### Project: Email Spam Classification

Decision Tree uses a tree-like structure to make predictions through a series of feature-based decisions.

### Important Parameters

- criterion
- max_depth
- min_samples_split
- min_samples_leaf

### Evaluation

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

### Visualization

Decision Tree structure is visualized using `plot_tree()`.

---

## 9. Support Vector Machine (SVM)

### Project: Loan Approval Prediction

Support Vector Machine finds a decision boundary that separates different classes. SVM can be used for classification and regression. :contentReference[oaicite:0]{index=0}

### Common Kernels

- Linear
- Polynomial
- RBF
- Sigmoid

### Important Parameters

- C
- kernel
- gamma

### Preprocessing

StandardScaler is applied because SVM is sensitive to feature scale.

### Evaluation

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## 10. AdaBoost

### Project: Customer Churn Prediction

AdaBoost is an ensemble learning algorithm that combines multiple weak learners to build a stronger model.

### Important Parameters

- n_estimators
- learning_rate
- base_estimator

### Evaluation

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## 11. Gradient Boosting Classifier

### Project: Customer Churn Prediction

Gradient Boosting builds models sequentially, where each new model attempts to improve the errors made by previous models.

### Dataset Features

- Age
- Monthly_Charges
- Total_Charges
- Tenure_Months
- Number_of_Services
- Support_Calls
- Contract_Length
- Payment_Delay_Days

### Target

`Churn`

- Yes
- No

### Important Parameters

- n_estimators
- learning_rate
- max_depth
- min_samples_split
- min_samples_leaf

### Hyperparameter Tuning

`GridSearchCV`

### Evaluation

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## 12. XGBoost

### Project: Customer Churn Prediction

XGBoost is an optimized gradient boosting algorithm that builds decision trees sequentially and uses regularization and efficient training techniques.

### Dataset Features

- Age
- Monthly_Charges
- Total_Charges
- Tenure_Months
- Number_of_Services
- Support_Calls
- Contract_Length
- Payment_Delay_Days

### Target

`Churn`

- Yes
- No

### Important Parameters

- n_estimators
- learning_rate
- max_depth
- subsample
- colsample_bytree

### Hyperparameter Tuning

`GridSearchCV`

### Feature Importance

XGBoost feature importance is used to identify which features contribute most to predictions.

---

# 🔧 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook
- Visual Studio Code
- Git
- GitHub

---

# 📊 Machine Learning Workflow

```text
Dataset
   ↓
Data Understanding
   ↓
Data Cleaning
   ↓
Missing Value Handling
   ↓
Outlier Detection
   ↓
Feature Selection
   ↓
Train-Test Split
   ↓
Feature Scaling
   ↓
Model Training
   ↓
Hyperparameter Tuning
   ↓
Prediction
   ↓
Model Evaluation
   ↓
Feature Importance
