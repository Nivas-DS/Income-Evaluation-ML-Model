# Income Evaluation Prediction – Machine Learning Project

### 📌 Objective
Predict whether a person's income is `>50K` or `<=50K` per year using the Adult Census Income dataset.
This project includes complete EDA, feature engineering, sampling techniques, and model building.

---

## 📊 Dataset Overview
- Categorical + Numerical columns
- Imbalanced target variable
- Several skewed variables such as:
  - capital_gain
  - capital_loss
  - final_census

---

## 🛠️ Steps Performed

### 1️⃣ Data Cleaning
- Removed a column with many NaN values  
- Trimmed column names  
- Removed duplicate rows  
- Separated numerical & categorical features  
- Imputed missing values  

### 2️⃣ Exploratory Data Analysis (EDA)
- Univariate, bivariate, multivariate analysis  
- Identified skewness + outliers  
- Observed that:
  - Target is imbalanced  
  - `final_census` has strong outliers  
  - Education is dominated by HS-Grad & Some-college  

### 3️⃣ Handling Imbalance
Used:
- **SMOTE**
- **SMOTEENN**
- **Undersampling**

### 4️⃣ Model Building
Trained multiple models using:
- Random Forest
- Decision Trees
- Logistic Regression
- GridSearchCV for tuning

### 🏆 Best Model
- **Random Forest + GridSearchCV + SMOTE**
- Best balance between accuracy and generalization.

---

## 📁 Files in This Repository
- `Income_Evaluation.ipynb` → Full ML notebook  
- `Results of ML Model on Income Evaluation.pptx` → Presentation summary  
- `requirements.txt` (optional)  

---

## 🚀 Future Improvements
- Use XGBoost/LightGBM  
- Deploy the model (Streamlit/Flask)  
- Add feature importance + SHAP  

---

## ✨ Author
**Nivas D**
