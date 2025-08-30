# 🛳 Titanic Survival Prediction

This project is a beginner-friendly **Machine Learning classification project** using the famous [Titanic dataset](https://www.kaggle.com/c/titanic).  
The goal is to predict whether a passenger survived or not based on features like age, sex, class, and more.

---

## 📂 Project Overview
- **Data Source:** Titanic dataset (Kaggle)  
- **Goal:** Predict passenger survival (binary classification)  
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Scikit-learn  

---

## 🔑 Key Steps
1. **Data Cleaning & Preprocessing**  
   - Handled missing values (Age, Embarked, Cabin).  
   - Converted categorical features (Sex, Embarked) into numerical form.  

2. **Exploratory Data Analysis (EDA)**  
   - Visualized survival rates by gender, class, and age groups.  

3. **Model Building**  
   - Trained Logistic Regression, Decision Tree, and Random Forest models.  
   - Compared model performance with accuracy and cross-validation.  

4. **Results**  
   - Achieved **~80% accuracy** on test data with Random Forest.  

---

## 📊 Visualizations
- Survival rate by gender and class  
- Age distribution of survivors vs non-survivors  
- Feature importance plot (from Random Forest)  

---

## 🚀 How to Run
1. Clone this repository  
   ```bash
   git clone https://github.com/your-username/titanic-survival.git
   cd titanic-survival
Install dependencies

bash
Copy code
pip install -r requirements.txt
Open the Jupyter Notebook

bash
Copy code
jupyter notebook Titanic.ipynb
