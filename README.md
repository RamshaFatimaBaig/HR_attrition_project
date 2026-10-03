# HR Analytics – Employee Attrition Prediction

## Project Overview

This project focuses on analyzing employee attrition and identifying factors associated with employees leaving an organization. Machine learning models were developed to predict employee attrition, while Power BI was used to create an interactive dashboard for visualization and analysis.

The project uses the IBM HR Analytics Employee Attrition dataset, which contains information about employee demographics, job roles, income, satisfaction, work experience, and attrition.

## Objectives

* Analyze employee attrition patterns.
* Identify factors associated with employee turnover.
* Perform data cleaning and exploratory data analysis.
* Engineer relevant features for machine learning.
* Train classification models to predict employee attrition.
* Compare model performance using appropriate evaluation metrics.
* Create an interactive Power BI dashboard.
* Provide recommendations for reducing employee attrition.

## Technologies Used

* Python
* Pandas
* Scikit-learn
* Matplotlib
* Seaborn
* SHAP
* Jupyter Notebook
* Power BI
* Microsoft Word / PDF

## Dataset

The project uses the IBM HR Analytics Employee Attrition dataset.

* Total employees: 1,470
* Target variable: Employee Attrition
* Dataset includes information such as:

  * Age
  * Gender
  * Department
  * Job Role
  * Monthly Income
  * Job Satisfaction
  * Years at Company
  * Work-Life Balance
  * Overtime
  * Job Level
  * Business Travel
  * And other HR-related attributes

## Project Workflow

### 1. Data Cleaning

* Checked the dataset for missing values and inconsistencies.
* Removed unnecessary columns.
* Prepared numerical and categorical variables for analysis.

### 2. Exploratory Data Analysis

* Analyzed employee demographics.
* Examined attrition across departments and job roles.
* Studied factors such as income, overtime, job satisfaction, and experience.
* Created visualizations to identify important patterns.

### 3. Feature Engineering

* Created and transformed relevant features.
* Encoded categorical variables.
* Prepared the dataset for machine learning.
* Scaled numerical features where required.

### 4. Machine Learning

Three classification models were trained:

* Logistic Regression
* Decision Tree
* Random Forest

The dataset was divided into training and testing sets using an 80/20 stratified split.

Since employee attrition is an imbalanced classification problem, the models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

### 5. Model Explainability

SHAP (SHapley Additive exPlanations) was used to analyze feature contributions and improve the interpretability of the machine learning model.

### 6. Power BI Dashboard

An interactive Power BI dashboard was developed to visualize:

* Total employees
* Employees who left
* Attrition patterns
* Employee demographics
* Job-related factors
* Income and experience
* Other HR-related insights

### 7. Attrition Prevention Suggestions

Recommendations were prepared based on the analysis to highlight areas that organizations can consider when developing employee retention strategies.

## Model Results

The models were evaluated on the test dataset.

| Model               | Accuracy |
| ------------------- | -------: |
| Logistic Regression |   86.05% |
| Decision Tree       |   83.33% |
| Random Forest       |   83.33% |

Because the dataset is imbalanced, accuracy was not considered alone. Precision, recall, F1-score, and confusion matrices were also analyzed, particularly for the attrition class.

Detailed model results are available in the `Model Accuracy Report.pdf`.

## Project Files

| File                                    | Description                                          |
| --------------------------------------- | ---------------------------------------------------- |
| `Attrition.csv`                         | Original HR employee dataset                         |
| `HR Attrition Project.ipynb`            | Complete data analysis and machine learning notebook |
| `HR Attrition Grade.csv`                | Processed project dataset                            |
| `HR Analytics Attrition Dashboard.pbix` | Power BI dashboard                                   |
| `Model Accuracy Report.pdf`             | Model performance metrics and confusion matrices     |
| `Attrition Prevention Suggestions.pdf`  | Attrition analysis recommendations                   |

## Project Workflow Summary

```text
Dataset
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Feature Engineering
   ↓
Machine Learning
   ↓
Model Evaluation
   ↓
SHAP Analysis
   ↓
Power BI Dashboard
   ↓
Attrition Prevention Suggestions
```

## Key Outcomes

This project demonstrates an end-to-end HR analytics workflow combining:

* Data analysis
* Data visualization
* Feature engineering
* Machine learning
* Model evaluation
* Model explainability
* Business intelligence
* HR recommendations

The project provides insights into employee attrition patterns and demonstrates how data analytics and machine learning can be applied to HR-related decision-making.

## Conclusion

The HR Analytics Employee Attrition Prediction project combines data analysis, machine learning, model explainability, and Power BI visualization to study employee attrition. The analysis provides insights into factors associated with employee turnover and demonstrates an end-to-end approach to using data-driven methods in HR analytics.
