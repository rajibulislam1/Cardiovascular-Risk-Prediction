# Cardiovascular-Risk-Prediction
# Introduction:
The goal of this project is to predict whether a patient has a 10-year risk of coronary heart disease using a dataset containing various health-related features. The dataset consists of 3189 instances and 17 columns.

# Data Preprocessing:
* The initial step was to import relevant libraries and load the dataset. The dataset was explored to understand its structure and characteristics. There were missing values in columns such as 'education', 'cigsPerDay', 'BPMeds', 'totChol', 'BMI', 'heartRate', and 'glucose'. These missing values were imputed using different techniques depending on the column. Outliers were identified and removed for several columns such as 'totChol', 'sysBP', 'diaBP', 'BMI', 'heartRate', and 'glucose'. * * 
* Duplicated values were also checked for and removed, resulting in a cleaned dataset of 2746 instances and 17 columns.

# Exploratory Data Analysis (EDA):
* EDA was conducted to gain insights into the distribution of various features and their relationships.
* Visualizations included distribution plots for features like 'age', 'totChol', 'sysBP', 'diaBP', 'BMI', 'heartRate', and 'glucose'.
* Countplots were created for categorical features such as 'sex', 'is_smoking', 'BPMeds', 'prevalentStroke', 'prevalentHYP', 'diabetes', and 'TenYearCHD'. The distribution of cigsPerDay was also visualized using a count plot.

# Feature Engineering:
* Categorical features 'sex' and 'is_smoking' were encoded into binary values (0 and 1).
* Additionally, correlations between features were calculated to understand their relationships.

#Modeling:
* The data was split into features (X) and the target variable (y). A machine learning model was built using the cleaned dataset to predict the 'TenYearCHD' target variable.
* The model was evaluated using various metrics like accuracy, precision, recall, F1-score, and confusion matrix. Further tuning of model parameters was done using GridSearchCV.

# Conclusion:
* The project successfully achieved its goal of predicting the 10-year risk of coronary heart disease using health-related features. \
* The data preprocessing steps, exploratory data analysis, and model-building process were systematically carried out to obtain meaningful insights and accurate predictions.
* Further improvements could involve exploring more complex algorithms, feature selection, and incorporating domain knowledge to enhance model performance.




