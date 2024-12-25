# ML_TexasSalaryPred


Project Overview

This project focuses on analyzing salary data of employees across 113 state government agencies in Texas. 
The goal is to provide actionable insights, build a predictive model to estimate payroll information, and address key business questions related to wage disparities and salary trends. 
The analysis is designed to aid the Texas state government in making informed payroll management decisions.
________________________________________

Tasks and Deliverables

Task 1: Data Analysis Report

A detailed exploration of the provided dataset was conducted to extract insights:

•	Identified outliers in employee salaries.

•	Analyzed wage disparities across roles and departments.

•	Investigated changes in salaries and total compensation over time.


Task 2: Predictive Modeling

Developed a predictive model to estimate payroll information for employees. 
Various machine learning models were evaluated, and the best-performing model was recommended for production deployment.


Task 3: Business Questions

•	Identified outliers in employee salaries using statistical techniques.

•	Analyzed departments/roles with the largest wage disparities between managers and employees.

•	Explored temporal changes in salaries and compensations across roles, departments, and headcounts.
________________________________________
Dataset Information

The dataset includes salary information for positions at all 113 state agencies in Texas, obtained via the Texas Public Information Act.
Key attributes in the dataset include:

•	Agency and Agency Name

•	Employee Details: Last Name, First Name, Middle Initial (MI)

•	Position Information: Class Title, Status, Employ Date

•	Demographics: Ethnicity, Gender

•	Compensation Information: Hourly Rate, Hours per Week, Monthly Income, Annual Income

•	Other: State Number

________________________________________
Analysis and Insights

Key Findings

1.	Outliers:
   
o	Detected employees with unusually high or low salaries using statistical methods like the IQR (Interquartile Range).

o	These outliers were investigated to determine the reasons, such as unique job roles or errors.

2.	Wage Disparities:
   
o	Departments like [e.g., Department A, Department B] exhibited the largest wage disparities between managers and employees.

o	Highlighted roles where compensation differences were the most pronounced.

3.	Trends Over Time:
   
o	Salaries and compensations for certain departments increased significantly over the years.

o	Identified roles with stagnant or declining salaries.

________________________________________
Predictive Modeling

Model Development

•	Built a predictive model to estimate payroll information based on key features such as job title, employ date, and working hours.

•	Models compared included:

o	Linear Regression

o	Decision Tree Regressor

o	Random Forest Regressor

o	XGBoost

o	Gradient Boosting

Model Comparison

•	Evaluation Metrics: Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), R-squared (R²).

•	Best Model: Random Forest Regressor performed the best, offering a good balance between accuracy and generalization.
________________________________________
Recommendation:

The Random Forest Regressor is suggested for production due to its robustness and performance on unseen data.
________________________________________
Challenges Faced and Solutions

Challenges

1.	Missing Data:
   
o	Handled missing values using mean/mode imputation and advanced techniques like KNN imputation for numerical features.

2.	Outliers:
   
o	Applied statistical methods such as Z-scores and IQR for outlier detection and removal.

3.	Feature Engineering:
   
o	Created new features like “Years of Service” and “Hourly Income” for better predictions.

4.	Imbalanced Data:
    
o	Addressed class imbalance in categorical features using SMOTE or re-sampling techniques.

5.	Model Overfitting:
    
o	Regularized models using hyperparameter tuning to avoid overfitting on the training data.
________________________________________
Tools and Techniques Used

•	Data Analysis: Python (pandas, NumPy, Matplotlib, Seaborn)

•	Predictive Modeling: Scikit-learn, XGBoost

•	Statistical Techniques: Z-scores, IQR for outlier detection, Pearson correlation for feature relationships
________________________________________
Results and Recommendations

•	Outliers should be reviewed and investigated for errors or exceptional cases.

•	Departments with significant wage disparities should be assessed for fairness and transparency in payroll.

•	The Random Forest model can be integrated into government systems for payroll estimation and budget planning.




