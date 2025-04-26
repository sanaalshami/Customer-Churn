# 📊 Telco Customer Churn Analysis
# 📝 Overview
This project aims to analyze customer churn in a telecommunications company (Telco). The main goal is to understand the factors affecting churn and build predictive models to classify customers as likely to churn or not.

# 📁 Dataset
The dataset used in this project is:
Telco Customer Churn

Rows: 7,043

Features: 21 (including categorical and numerical columns)

# 🔧 Tools & Libraries
Pandas, NumPy: Data manipulation

Matplotlib, Seaborn: Data visualization

Scikit-learn: Preprocessing, modeling, evaluation

XGBoost: Gradient boosting model

imblearn: SMOTE for handling class imbalance

# 🔍 Steps Performed
1. Data Loading and Exploration
Read CSV file and inspected using .info(), .describe(), and .head().

Checked for null values.

Dropped unnecessary columns (e.g., customerID).

Converted TotalCharges to numeric.


# 2. Exploratory Data Analysis (EDA)
Plotted histograms for numerical features (tenure, MonthlyCharges, TotalCharges).

Count plots for categorical features.

Heatmap to check correlation between numerical variables.

# 3. Preprocessing
Label encoding or one-hot encoding applied to categorical features.

Feature scaling using StandardScaler or MinMaxScaler.

SMOTE used to handle imbalanced target variable (Churn).

# 4. Modeling
Tested and compared several classification models:

Decision Tree

Random Forest

Support Vector Classifier (SVC)

XGBoost

Evaluated using:

Accuracy Score

Confusion Matrix

Classification Report




