#avc-attrition-analysis

Machine learning analysis for Case Studies in Data Science - Individual Tasks 1 and 2.

Two models: Logistic Regression and Decision Tree trained on the IBM Employee Attrition dataset to predict employee attrition, in the context of a People Data & Insights Analyst role at Australian Venue Co.

Dataset source: https://github.com/IBM/employee-attrition-aif360/blob/master/data/emp_attrition.csv

Notebooks:

attrition-analysis.ipynb (Task 1) - builds and evaluates the two models using accuracy, precision, recall and F1-score, and reports the top features for each.

deliberation-analysis.ipynb (Task 2) - extends the Task 1 models with:
1. Stratified 5-Fold Cross-Validation
2. Learning curves (training vs. validation F1-score across training set sizes)
3. A Fairlearn bias analysis across Gender and Age groups

Requirements -
pip install pandas scikit-learn matplotlib fairlearn
