# Using Machine learning (Classification) modelling to predict employee_attrition
Part of the Google Advanced Data Analytics Certification - Capstone
## Understand the business scenario and problem
The HR department at Salifort Motors wants to take some initiatives to improve employee satisfaction levels at the company. They collected data from employees, but now they don’t know what to do with it. They refer to you as a data analytics professional and ask you to provide data-driven suggestions based on your understanding of the data. 



Your goals in this project are to 
## **analyze the data collected by the HR department and to build a model that predicts whether or not an employee will leave the company**.
### They have the following question: what’s likely to make the employee leave the company?

If you can predict employees likely to quit, it might be possible to identify factors that contribute to their leaving. Because it is time-consuming and expensive to find, interview, and hire new employees, increasing employee retention will be beneficial to the company.


## 1. Introduction and Objective
The notebook begins by outlining the project's objective: to predict whether an employee is likely to leave the company (attrition) based on various features. This is a classic binary classification problem where the target variable is 'Attrition' (Yes/No).

## 2. Data Loading and Exploration
Data Import: The dataset is loaded using pandas. The dataset likely contains various features related to employee demographics, job roles, satisfaction levels, etc.

Initial Exploration: The notebook displays the first few rows of the dataset to get an overview of the data structure.

Data Types and Missing Values: It checks for data types of each column and identifies any missing values that need to be addressed.

## 3. Data Preprocessing
Handling Missing Values: If there are missing values, appropriate strategies such as imputation or removal are applied.

Encoding Categorical Variables: Categorical features are converted into numerical representations using techniques like Label Encoding or One-Hot Encoding to make them suitable for machine learning algorithms.

Feature Selection: Irrelevant or redundant features may be dropped to improve model performance.

Feature Scaling: Numerical features are scaled using techniques like StandardScaler to ensure that all features contribute equally to the model training.

## 4. Exploratory Data Analysis (EDA)
Visualization: The notebook includes various plots such as histograms, box plots, and correlation heatmaps to understand the distribution of features and relationships between them.

Insights: Key insights are drawn from the EDA, such as identifying features that have a strong correlation with the target variable.

## 5. Model Building
Train-Test Split: The dataset is split into training and testing sets to evaluate model performance on unseen data.

Model Selection: Various classification algorithms are considered, such as Logistic Regression, Decision Trees, Random Forests, and Support Vector Machines.

Model Training: Selected models are trained on the training data.

Hyperparameter Tuning: Techniques like Grid Search or Random Search are used to find the optimal hyperparameters for the models.

## 6. Model Evaluation
Predictions: The trained models make predictions on the test set.

Performance Metrics: Evaluation metrics such as Accuracy, Precision, Recall, F1-Score, and ROC-AUC are calculated to assess model performance.

Confusion Matrix: A confusion matrix is plotted to visualize the performance of the classification models.

## 7. Model Comparison and Selection
Comparative Analysis: The performance metrics of different models are compared to select the best-performing model.

Feature Importance: For models like Random Forest, feature importance is analyzed to understand which features contribute most to the prediction.

## 8. Conclusion and Future Work
Summary: The notebook concludes by summarizing the findings and the performance of the selected model.

Recommendations: Suggestions for future improvements, such as collecting more data, feature engineering, or trying advanced algorithms, are discussed.

## 9. Appendix
Code Snippets: Any additional code, functions, or processes used in the analysis are included in the appendix for reference.
[Jupyter Notebook](https://github.com/SatyJais/Predicting_employee_attrition/blob/main/google-ada-certification-capstone.ipynb)
