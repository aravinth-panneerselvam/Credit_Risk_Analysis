# Credit_Risk_Analysis
This project builds a Credit Risk Prediction model to estimate the probability of loan default using historical banking data. The objective is to help financial institutions minimize risk by identifying high-risk borrowers before loan approval.

The model predicts Probability of Default (PD) using Logistic Regression and statistical validation techniques.

# Problem Statement
Loan defaults cause significant financial losses for banks and lending institutions.
This project aims to:
* Predict whether a borrower will default
* Quantify default risk using probability scores
* Enable data-driven credit approval decisions

Tech Stack: Python | Numpy | Matplotlib Seaborn | Pandas | Statsmodels | Scikit Learn

# ⚙️ Project Workflow
1️⃣ Data Preprocessing
- Missing value treatment
- Outlier handling
- Variable transformation (bucketing)
- Encoding categorical variables

2️⃣ Exploratory Data Analysis
- Distribution analysis
- Default rate comparison
- Correlation study

3️⃣ Feature Engineering
- Binning numerical variables into deciles
- Multicollinearity check using Variance Inflation Factor (VIF)
- Feature selection

4️⃣ Model Building
- Logistic Regression model
- Probability prediction for default

5️⃣ Model Evaluation
- ROC Curve
- AUC Score

# 📈 Model Performance
- AUC Score: 0.84
- Performance evaluated using ROC-AUC for classification strength
<img width="586" height="393" alt="image" src="https://github.com/user-attachments/assets/5bc73a59-db2f-44dc-b6ce-54015d6ffea5" />

- Confusion Matrix
<img width="442" height="300" alt="image" src="https://github.com/user-attachments/assets/3789ef4a-80bf-4121-8e27-2b02f493fa9f" />

# Key Learnings
- Applied statistical modeling to real-world financial risk
- Understood business-driven threshold optimization
- Practiced multicollinearity diagnostics (VIF)
- Built an interpretable and production-relevant ML pipeline




