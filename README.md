📚 Project Overview:

This project involves using machine learning techniques to assist the HR Department in identifying key factors contributing to attrition, clustering employees based on satisfaction and evaluation, and suggesting targeted retention strategies.

🧰 Tools and Technologies Used

**Programming Language**: Python

**Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Imbalanced-learn

**Clustering Algorithm**: K-means

**Machine Learning Models**: Logistic Regression, Random Forest, Gradient Boosting

**Data Balancing Technique**: SMOTE (Synthetic Minority Oversampling Technique)

**Model Evaluation**: k-fold Cross-Validation

📈 Project Workflow

1. Data Quality Checks : 
Checked for missing values, inconsistencies, and outliers.
Verified data integrity to ensure reliable analysis.
2. Exploratory Data Analysis (EDA) : 
Visualized key trends in employee turnover using bar charts, scatterplots, and heatmaps.
Analyzed correlations between features like satisfaction, salary level, and attrition rates.
3. Clustering : 
Performed clustering on employees who left the company based on their SatisfactionLevel and LastEvaluation scores.
Visualized clusters to identify distinct employee groups.
4. Handling Class Imbalance : 
Addressed the imbalance in the target variable (Left) using SMOTE to generate synthetic samples.
5. Model Training and Validation : 
Performed k-fold cross-validation to ensure robust model evaluation.
Trained multiple models, including Logistic Regression, Random Forest, and Gradient Boosting.
6. Model Evaluation : 
Evaluated models using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.
Identified the best-performing model for deployment.
7. Retention Strategies : 
Suggested targeted retention strategies based on insights from the data and clusters.

🔑 Key Results
Best Performing Model
Model: [Gradient Boost]
Accuracy: [98.4]%
Precision: [96]%
Recall: [97]%
F1-Score: [97]%

Key Insights:

Low satisfaction scores and poor evaluations were the most significant predictors of turnover.
Employees with low salary levels were more likely to leave.
Employees who worked long hours but received no promotions had a higher likelihood of attrition.

Retention Strategies

Improve Employee Satisfaction:
Conduct regular surveys to measure and address satisfaction levels.
Provide flexible working hours and work-life balance programs.

Enhance Career Development:
Offer skill enhancement training and career progression plans.
Acknowledge high-performing employees through promotions or rewards.

Address Overwork Issues:
Monitor workloads and redistribute tasks to avoid burnout.
Implement automated tools to reduce manual workloads.

