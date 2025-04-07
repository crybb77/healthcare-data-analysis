![Health](Health_Photo.png)

**Objective** The notebook aims to build a machine learning model to predict diabetes status (Yes, No, Prediabetes) using a healthcare dataset.

**Methodology**

**Data Exploration and Cleaning:** The notebook begins with exploratory data analysis (EDA) to understand the data. This includes handling missing values, cleaning inconsistent data in the 'CLASS' and 'Gender' columns, and creating a new feature called 'age_range'.

**Feature Engineering:** The 'age_range' feature is engineered by grouping ages into 10-year intervals.

**Model Selection:** Several classification models are considered, including Logistic Regression, K-Nearest Neighbors, Naive Bayes, Support Vector Classifier, Random Forest, Decision Tree, and XGBoost. These models are evaluated using 5-fold cross-validation.

**Model Evaluation:** The XGBoost model emerges as the best performer based on cross-validation accuracy. Its performance is further evaluated on a test dataset using accuracy, classification report, and confusion matrix.

**Key Findings:**

The XGBoost Classifier achieved the highest accuracy in predicting diabetes status.
The dataset exhibited class imbalance, with more "No" diabetes cases than "Yes" or "Prediabetes".
Feature engineering, particularly the creation of the 'age_range' feature, contributed to model performance.

**Conclusion:**

The notebook demonstrates the application of machine learning for diabetes prediction. By leveraging data cleaning, feature engineering, and model selection techniques, the XGBoost Classifier achieved promising results. The insights gained from this analysis can be valuable for healthcare professionals in diabetes risk assessment and early intervention.
