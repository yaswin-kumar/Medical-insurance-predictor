# Medical-insurance-predictor

A Machine Learning web application that predicts individual medical insurance premiums based on health, demographic, and lifestyle factors.

This project utilizes regression algorithms to analyze user data (such as age, BMI, smoking status, and region) to estimate annual healthcare insurance costs, helping users understand the financial impact of health-related habits.

🚀 Features
Accurate Cost Estimation: Leverages trained ML models (e.g., Random Forest / Linear Regression) to predict charges.

Data-Driven Insights: Simple visualizations showing how key features like smoking or BMI disproportionately impact premium pricing.

🛠️ Tech Stack & Architecture

Language: Python
ML Libraries: Scikit-Learn, Pandas, NumPy
Visualization: Matplotlib, Seaborn

📊 Dataset Overview

The model is trained on a medical cost personal dataset containing the following features
:age: Age of primary beneficiary 

sex: Insurance contractor gender (female, male)

bmi: Body Mass Index ($kg/m^2$),

providing an objective index of body weight relative to heightchildren: Number of children/dependents covered by health insurance

smoker: Smoking status (yes, no)

region: The beneficiary's residential area in the US (northeast, southeast, southwest, northwest)

Target Variable - charges: Individual medical costs billed by health insurance
