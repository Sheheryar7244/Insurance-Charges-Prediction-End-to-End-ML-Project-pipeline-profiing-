# 💰 Insurance Charges Prediction — End-to-End Machine Learning Project

## 📌 Project Overview
This project is an end-to-end Machine Learning pipeline that analyzes an insurance dataset and predicts medical insurance charges based on personal attributes.

It includes:
- Exploratory Data Analysis (EDA)
- Automated data profiling
- Data preprocessing pipeline
- Machine Learning model (Random Forest)
- Feature importance analysis

---
## 📊 Dataset Description

| Feature | Description |
|--------|------------|
| age | Age of the individual |
| sex | Gender (male/female) |
| bmi | Body Mass Index |
| children | Number of dependents |
| smoker | Smoking status |
| region | Residential region |
| charges | Medical insurance cost (target variable) |

---
## 🔍 Exploratory Data Analysis (EDA)

Performed detailed analysis including:

### 📊 Univariate Analysis
- Histograms
- Count plots
- Distribution analysis

### 📈 Bivariate Analysis
- Age vs Charges
- BMI vs Charges
- Smoker vs Charges (very strong impact observed 🚬)

### 🔥 Multivariate Analysis
- Pair plots
- Correlation heatmap
- Pivot tables
- <img width="777" height="560" alt="image" src="https://github.com/user-attachments/assets/1d5d5554-31fa-4672-9133-3f000cad4b9f" />


---
## ⚡ Automated Data Profiling
Generated using **ydata-profiling**

The report includes:
- Missing values analysis
- Feature distributions
- Correlation analysis
- Data quality insights
- Warnings & statistics summary

📸 **Profiling Report Screenshots:**
<img width="1441" height="659" alt="image" src="https://github.com/user-attachments/assets/4294e711-8807-4452-a42a-6a1851919bc4" />
<img width="1539" height="536" alt="image" src="https://github.com/user-attachments/assets/ba83d677-9dc3-4360-ada0-88dc353ca575" />
<img width="1575" height="551" alt="image" src="https://github.com/user-attachments/assets/ce6a4828-2636-4614-91a8-77d7e1b44555" />
<img width="917" height="613" alt="image" src="https://github.com/user-attachments/assets/cc634b94-3122-4a2b-90ca-cf2e74888a8e" />
<img width="719" height="596" alt="image" src="https://github.com/user-attachments/assets/15912a58-26fe-4560-a6c3-db05c1376a02" />

Example:
- Overview page
- Correlation heatmap
- Missing values section

---
## ⚙️ End-to-End ML Pipeline
<img width="533" height="277" alt="image" src="https://github.com/user-attachments/assets/aa33f7c0-307a-4fe5-a5fd-daf05127f81f" />
Built using **Scikit-learn Pipeline**

### 🔹 Steps:
1. Data preprocessing  
2. One-hot encoding of categorical variables  
3. Feature scaling for numeric features  
4. Model training  
5. Prediction  

---
## 🤖 Machine Learning Model

### Model Used:
- 🌳 Random Forest Regressor

### Why Random Forest?
- Handles non-linear relationships well  
- Reduces overfitting  
- Provides feature importance  

---
## 📊 Model Evaluation

- MAE (Mean Absolute Error)  
- RMSE (Root Mean Squared Error)  
- R² Score  (approx 0.87)
---
📊 Model Performance Visualization
📈 Actual vs Predicted (Random Forest Regressor)
To visually evaluate model performance, an Actual vs Predicted scatter plot was used.
Result:Model supports real-time prediction on new unseen data using trained pipeline.
<img width="558" height="547" alt="image" src="https://github.com/user-attachments/assets/c1d99379-5eeb-40e5-b8eb-af11ef9f3fed" />
📊 Interpretation of Results
Most predictions are close to the red line, showing strong model performance
The model performs well for low and medium insurance charges
Slight deviation is observed at higher charge values
Overall, the Random Forest model shows a strong correlation between actual and predicted values
---
## 🔥 Feature Importance Analysis

Extracted using trained Random Forest model:
<img width="372" height="267" alt="image" src="https://github.com/user-attachments/assets/35345f67-56d2-43f9-b92c-98f80ab378e2" />
---
🎯 Key Insights
Smokers pay significantly higher insurance charges
Age and BMI show strong positive correlation with charges
Most features are well-distributed
Model successfully captures non-linear patterns
---
🚀 What I Learned
End-to-end ML pipeline development
Exploratory Data Analysis (EDA) techniques
Automated profiling using ydata-profiling
Feature encoding & preprocessing
Random Forest regression modeling
Feature importance interpretation

🔥Sheheryar Khan (AI/ML) trained and evaluated this model
