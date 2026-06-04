# Heart-Disease-Prediction
Machine Learning project to predict heart disease using classification models like Random Forest, SVM, and Logistic Regression.

##  Overview

This project predicts the likelihood of heart disease in patients using machine learning techniques. It includes data analysis, feature engineering, and model comparison to identify individuals at risk and support early medical intervention.

##  Problem Statement

The goal is to build a predictive model that can identify whether a person is likely to have heart disease based on medical attributes. This helps hospitals take preventive actions and reduce life-threatening risks.

##  Dataset Features

* Age, Sex  
* Chest Pain Type  
* Resting Blood Pressure  
* Serum Cholesterol  
* Fasting Blood Sugar  
* Resting ECG Results  
* Maximum Heart Rate Achieved  
* Exercise Induced Angina  
* ST Depression (Oldpeak)  
* Slope of ST Segment  
* Number of Major Vessels  
* Thalassemia Test Result  

* Target: Presence of Heart Disease  

##  Steps Performed

* Data Cleaning & Preprocessing  
* Handling Missing Values  
* Exploratory Data Analysis (EDA)  
* Feature Engineering  
* Encoding Categorical Variables  
* Model Building (Logistic Regression, Decision Tree, Random Forest, SVM, Gradient Boosting)  
* Model Evaluation & Comparison  

##  Model Performance

| Model                | Accuracy | Precision | Recall | F1 Score | ROC-AUC |
|---------------------|---------|----------|--------|----------|---------|
| Logistic Regression | 0.8333  | 0.7778   | 0.8750 | 0.8235   | 0.9406  |
| Decision Tree       | 0.8333  | 0.8571   | 0.7500 | 0.8000   | 0.8422  |
| Random Forest       | 0.8611  | 0.7895   | 0.9375 | 0.8571   | 0.9469  |
| SVM                 | 0.8611  | 0.9231   | 0.7500 | 0.8276   | 0.9313  |
| Gradient Boosting   | 0.8889  | 0.8333   | 0.9375 | 0.8824   | 0.9656  |

 **Best Model: Random Forest** (Highest Accuracy & ROC-AUC)

---

##  Technologies Used

* Python  
* Pandas, NumPy  
* Scikit-learn  
* Matplotlib, Seaborn  

##  Dataset

The dataset used in this project is available here:  
https://d3ilbtxij3aepc.cloudfront.net/projects/CDS-Capstone-Projects/PRCP-1016-HeartDieseasePred.zip

##  Challenges Faced

* Handling mixed data types (categorical + numerical medical features)  
* Managing missing or inconsistent medical records  
* Preventing overfitting due to limited dataset size  
* Selecting the most relevant features for prediction  
* Ensuring model interpretability for healthcare use  

##  Future Work

* Apply advanced models like XGBoost and Deep Learning  
* Perform extensive hyperparameter tuning  
* Integrate real-time patient data for live predictions  
* Deploy the model using Flask or Streamlit  
* Improve accuracy using larger and more diverse datasets  
