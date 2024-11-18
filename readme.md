**Insurance Charges Prediction

This project aims to predict insurance charges using a linear regression model. The dataset contains various features such as demographic information, health indicators, and past medical history, which are utilized to understand the factors influencing insurance charges.

**Dataset Overview**
The dataset consists of 1338 entries with the following columns:

age-->	Age of the individual
sex-->	Gender of the individual
bmi-->	Body Mass Index	
children-->	Number of children
smoker-->	Smoking status (Yes/No)
Claim_Amount-->	Amount claimed for insurance
past_consultations-->	Number of past medical consultations
num_of_steps-->	Average daily step count
Hospital_expenditure-->	Total hospital expenditure
NUmber_of_past_hospitalizations	Number of past hospitalizations	Float
Anual_Salary	Annual salary of the individual	Float
region	Region of residence	Object
charges	Insurance charges (target variable)	Float
Some columns contain missing values that were handled as part of the preprocessing pipeline.

**Methodology**
Exploratory Data Analysis (EDA)

Analyzed distributions of numerical features.
Investigated relationships between features and the target variable (charges).
Data Preprocessing

Handled missing values using appropriate imputation techniques.
Detected and treated outliers using the Interquartile Range (IQR) method to improve data quality and model robustness.
Multicollinearity Analysis

Performed Variance Inflation Factor (VIF) analysis to identify and address multicollinearity among numerical features.
Model Development

Developed a linear regression model to predict charges.
Split the data into training and testing sets for evaluation.
Evaluated the model using metrics such as Mean Squared Error (MSE) and R-squared (R²).
Visualization

Utilized matplotlib to visualize correlations, feature importance, and model performance.
**Libraries Used**
The project is implemented in Python using the following libraries:

pandas: Data manipulation and analysis.
numpy: Numerical computations.
matplotlib: Data visualization.
scikit-learn: Machine learning model development and evaluation.
