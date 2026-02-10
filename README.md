# 🏦 Loan Approval Prediction System

## 📌 Project Overview
The **Loan Approval Prediction System** is a machine learning project developed using Python and Jupyter Notebook. Its main goal is to predict whether a loan application will be **approved or rejected** based on applicant details such as income, loan amount, credit history, and property area.

This project demonstrates the practical application of **data preprocessing, exploratory data analysis (EDA), feature engineering, and machine learning models** to solve a real-world financial problem.

---

## 🎯 Objectives
- Analyze loan applicant data
- Clean and preprocess raw data
- Perform exploratory data analysis
- Build and evaluate machine learning models
- Predict loan approval status accurately
- Identify key factors affecting loan approval

---

## 📂 Dataset Description
The dataset contains information about loan applicants.

### Features:
- Applicant Income  
- Coapplicant Income  
- Loan Amount  
- Loan Amount Term  
- Credit History  
- Gender  
- Marital Status  
- Education  
- Self Employed  
- Property Area  

### Target Variable:
- **Loan_Status** (Approved / Not Approved)

---

## 🛠️ Technologies Used
- **Programming Language:** Python  
- **Environment:** Jupyter Notebook  

### Libraries:
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  

---

## 🔄 Detailed Steps Description

### Step 1: Import Libraries
Import all necessary Python libraries for data manipulation, visualization, and machine learning.

### Step 2: Load the Dataset
Load the dataset using pandas and inspect it to understand its structure, features, and data types.

### Step 3: Explore the Dataset
Check for missing values, data types, and basic statistics. Understand numerical and categorical features.

### Step 4: Handle Missing Values
Fill missing numerical values using mean/median and categorical values using mode.

### Step 5: Data Cleaning
Remove duplicates, correct inconsistencies, and drop irrelevant columns.

### Step 6: Encode Categorical Variables
Convert categorical features into numerical values using label encoding or one-hot encoding.

### Step 7: Exploratory Data Analysis (EDA)
Visualize distributions and relationships between features and the target variable using plots and charts.

### Step 8: Feature Selection
Identify important features and remove redundant ones to improve model performance.

### Step 9: Split Data
Divide the dataset into training and testing sets to evaluate model performance on unseen data.

### Step 10: Model Training
Train machine learning models such as Logistic Regression, Decision Tree, and Random Forest using the training dataset.

### Step 11: Model Evaluation
Evaluate the trained models on the testing set using accuracy, confusion matrix, and other metrics.

### Step 12: Prediction
Use the trained model to predict loan approval for new applicant data.

### Step 13: Result Analysis
Analyze results to identify key factors affecting loan approval.

### Step 14: Conclusion and Future Scope
Summarize key findings and propose improvements, such as advanced models, hyperparameter tuning, or deployment.

---

## ▶️ How to Run the Project

1. Clone the repository:
```bash
git clone https://github.com/Rutudabhade13/Loan-Approval.git

## Model Accuracy & Results:

After training and evaluating the machine learning models on the loan dataset, the following results were observed:

Model	Accuracy (%)
Logistic Regression	81–83
Decision Tree Classifier	78–80
Random Forest Classifier	84–86

Note: Accuracy may vary depending on preprocessing and train-test split. In most experiments, Random Forest Classifier gave the best performance.

Confusion Matrix Example (Random Forest):

                 Predicted Approved | Predicted Not Approved
Actual Approved        90                     12
Actual Not Approved    10                     45


Observations:

Credit History is the most influential feature for loan approval.

Applicant Income and Loan Amount are also significant factors.

Most misclassifications occur for borderline applicants with incomplete credit history.

✅ Conclusion

The Loan Approval Prediction System demonstrates how machine learning can assist financial institutions in automating loan decisions. Key conclusions from the project:

Machine learning models can accurately predict loan approvals based on applicant data, helping reduce manual effort.

Random Forest Classifier achieved the highest accuracy, indicating ensemble methods perform well on this dataset.

Credit history, applicant income, and loan amount are the most significant factors influencing loan approval.

With proper preprocessing, feature selection, and model evaluation, predictive accuracy of 85% or more is achievable.

Future improvements could include:

Hyperparameter tuning for better accuracy

Testing advanced algorithms like XGBoost or Gradient Boosting

Deploying the model as a web or mobile application for real-time loan assessment
