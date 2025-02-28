# Salifort Motors HR Analytics Project

## Project Overview
This project aims to provide data-driven insights to the Human Resources (HR) department of Salifort Motors, a large consulting firm. The focus is on analyzing employee data and predicting whether an employee is likely to leave the company. The project utilizes either a regression model or a machine learning classification model to achieve this goal.

## Data Description
The dataset includes various attributes related to employees, such as:
- **Employee Satisfaction Score**: A numerical rating of employee satisfaction.
- **Last Evaluation Score**: Employee performance evaluation.
- **Number of Projects**: Number of projects assigned to the employee.
- **Average Monthly Hours**: Time spent at work.
- **Time Spent at Company**: Duration of employment.
- **Work Accident**: Indicator of workplace incidents.
- **Promotion in Last 5 Years**: Whether the employee received a promotion.
- **Department**: The department in which the employee works.
- **Salary Level**: Categorized as low, medium, or high.
- **Turnover Status**: Target variable (whether an employee leaves the company).

## Approach and Methodology
### 1. Data Preprocessing
- **Handling Missing Values**: Checked for null values and handled them accordingly.
- **Feature Encoding**: Converted categorical features like salary level and department into numerical values.
- **Feature Scaling**: Standardized numerical variables for optimal model performance.

### 2. Exploratory Data Analysis (EDA)
- **Distribution Analysis**: Examined key employee metrics such as satisfaction score and monthly working hours.
- **Correlation Analysis**: Identified relationships between variables.
- **Turnover Trends**: Visualized key factors affecting employee attrition.

### 3. Model Development
Two modeling approaches were considered:
#### a) Logistic Regression
- **Used for Binary Classification**: Predicted whether an employee will leave or stay.
- **Feature Selection**: Used statistical tests to choose the most important predictors.
- **Model Evaluation Metrics**: Accuracy, precision, recall, and F1-score.

#### b) Machine Learning Models (Decision Tree, Random Forest, or XGBoost)
- **Trained multiple models** to determine the best-performing one.
- **Hyperparameter Tuning**: Used GridSearchCV to optimize model performance.
- **Feature Importance Analysis**: Assessed which features contribute most to turnover prediction.

### 4. Model Evaluation
- **Confusion Matrix**: Assessed classification performance.
- **ROC-AUC Score**: Measured the model’s ability to distinguish between employees who stay and those who leave.
- **Feature Importance Analysis**: Provided insights into key factors driving turnover.

## Key Findings
- Employees with **low satisfaction scores** are significantly more likely to leave.
- **Long working hours** combined with **low salary levels** contribute to higher turnover rates.
- Employees with **fewer projects** or those **without recent promotions** tend to leave.
- **Certain departments** have higher attrition rates than others, indicating potential internal issues.

## Conclusion
The insights gained from this project can help Salifort Motors’ HR team take proactive measures to retain employees, reduce turnover, and create a better work environment.

## Tools & Technologies Used
- **Python**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Jupyter Notebook**: For coding and documentation
- **Machine Learning Models**: Logistic Regression, Decision Tree, Random Forest, XGBoost

## Next Steps
- Deploy the best-performing model into an HR dashboard.
- Implement real-time monitoring of employee satisfaction trends.
- Conduct further analysis on department-specific attrition causes.
