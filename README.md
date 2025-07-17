❤️ Heart Disease Prediction using Machine Learning
📌 Project Overview

This project explores the use of machine learning algorithms to predict the likelihood of heart disease based on patient clinical data. The primary goal is to develop a reliable and accurate predictive model that can aid healthcare professionals in early diagnosis and decision-making.

🎯 Aim

- To build a machine learning model that can predict whether a patient has heart disease using features derived from the Cleveland Heart Disease dataset, with a target accuracy of at least 95%.

🧪 Techniques and Methodology

🔍 Data Analysis & Preprocessing
- Data sourced from the UCI Machine Learning Repository (Cleveland dataset)

- Exploratory Data Analysis (EDA) to understand distribution, relationships and correlations

- Visualization tools used: Matplotlib, Seaborn

- No missing values in the dataset, so imputation was not required

- Correlation heatmap created to identify significant predictors

🧰 Libraries Used

- NumPy, Pandas for data handling

- Matplotlib, Seaborn for visualization

- Scikit-learn for modelling and evaluation

🏗️ Modelling Approach
Three classification models were trained:

- Logistic Regression

- K-Nearest Neighbors (KNN)

- Random Forest Classifier

Model selection was based on accuracy scores from initial fits:

 Logistic Regression: 88.5%

- Random Forest: 83.6%

- KNN: 68.9%

🧪 Advanced Evaluation & Tuning

- Hyperparameter tuning using RandomizedSearchCV for Logistic Regression and Random Forest

- Performance metrics assessed: precision, recall, F1-score, ROC-AUC

- Additional insights gathered from feature importance and confusion matrices

✅ Results & Outcome
- Logistic Regression emerged as the top-performing model, achieving 88.5% accuracy

- Feature importance and ROC curve analysis helped validate model reliability

- With further tuning, models showed potential to reach or approach the 95% benchmark

📊 Visual Insights
- Heart disease prevalence visualized across gender and chest pain types

- Age and maximum heart rate showed strong correlation with disease likelihood

🚀 Conclusion

This project successfully demonstrates how classical machine learning models can be applied to health data for predictive diagnostics. With proper tuning and validation, such tools hold immense promise for supporting clinical decisions.
