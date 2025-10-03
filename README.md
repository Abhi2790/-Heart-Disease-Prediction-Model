# ❤️ Heart Disease Prediction using Machine Learning

This project applies **machine learning models** to predict the presence of **heart disease** based on patient health records.  
It uses **classification algorithms** like Logistic Regression to analyze medical features and predict outcomes.  

---

## 📌 Features
- Data preprocessing (null checks, descriptive statistics)  
- Splitting dataset into features (X) and target (y)  
- Classification with **Logistic Regression**  
- Model evaluation using:  
  - **Accuracy Score**  
  - **Classification Report** (Precision, Recall, F1-score)  
  - **Confusion Matrix**  

---

## 📂 Dataset
- File: `heart.csv`  
- Each row represents patient health data.  
- Common features in the dataset include:
  - Age  
  - Sex  
  - Chest pain type (cp)  
  - Resting blood pressure (trestbps)  
  - Serum cholesterol (chol)  
  - Fasting blood sugar (fbs)  
  - Resting ECG results (restecg)  
  - Maximum heart rate achieved (thalach)  
  - Exercise induced angina (exang)  
  - Oldpeak (ST depression)  
  - Slope of peak exercise ST segment (slope)  
  - Number of major vessels (ca)  
  - Thalassemia (thal)  

- Target column:  
  - **output** → 0 (No Heart Disease) / 1 (Heart Disease Present)  

---

## Requirements

- Python 3.8+

- numpy, pandas, matplotlib

- scikit-learn

. Install via:
```
pip install numpy pandas matplotlib scikit-learn
```

---

## 🔮 Future Improvements

- Add more ML models (Random Forest, SVM, XGBoost)

- Hyperparameter tuning with GridSearchCV

- Feature importance visualization

- Deploy as a Streamlit app or Flask API

---

## 👨‍💻 Author

Abhishek Kumar

MCA (AI/ML) | ML & Data Science Enthusiast
