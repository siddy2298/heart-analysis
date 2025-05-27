# Heart Attack Prediction

This project aims to predict heart disease risk based on various patient health metrics. Leveraging the **K-Nearest Neighbors (KNN)** algorithm, this analysis focuses on identifying patterns in medical data and supporting healthcare decision-making through predictive insights.

---

## 📚 Dataset

- **Source**: [Kaggle Dataset: Heart Attack Analysis & Prediction](https://www.kaggle.com/datasets/rashikrahmanpritom/heart-attack-analysis-prediction-dataset)  
- **Publisher**: Rashik Rahman  
- **Last Updated**: 2021  
- **Data Points**: Patient demographics, medical history, test results

---

## 🧩 Features

✅ **Categorical Data**  
- **Sex**: Male (1), Female (0)  
- **Chest Pain Type**:  
  - ASY = 1 (Asymptomatic)  
  - ATA = 2 (Atypical Angina)  
  - NAP = 3 (Non-Anginal Pain)  
  - TA = 4 (Typical Angina)  
- **Exercise**: Yes (1), No (0)  
- **ST Slope Peak**: Up (1), Flat (0), Down (2)  

✅ **Numerical Data**  
- **Age**  
- **Blood Pressure**  
- **Cholesterol (mg/dl)**  
- **Max Heart Rate**  
- **Fasting Blood Sugar**  
- **Electrocardiographic Results**  
- **Heart Disease**: 1 (positive), 0 (negative)  

---

## ⚙️ Preprocessing

- Removed irrelevant columns (e.g., “oldpeck”)  
- Deleted duplicate and missing rows  
- Normalized categorical values for clarity  
- Renamed columns for consistency  

Using Python:  
1️⃣ Checked for `null` values  
2️⃣ Described dataset (mean, std, etc.)  
3️⃣ Separated categorical and numerical data  

---

## 🔍 Hypotheses & Analysis

### 1️⃣ Age & Gender Impact
- **Goal**: Identify which age groups and genders are most affected by heart disease.
- **Method**: KNN classifier based on age, gender, and target values.

### 2️⃣ Chest Pain Type
- **Goal**: Determine which chest pain types are most common in positive heart disease cases.
- **Method**: Visual analysis and KNN predictions based on pain type and age.

### 3️⃣ Cholesterol, Heart Rate & Exercise
- **Goal**: Examine the relationship between cholesterol, max heart rate, exercise habits, and heart disease risk.
- **Method**: KNN classifier using health metrics and target values.

---

## 🚀 Proposed Solution

✅ Implemented a **KNN classifier** to predict heart disease based on nearest neighbor relationships.  
✅ Steps:
1. Load dataset  
2. Preprocess and clean data  
3. Train KNN model (default `k=5`)  
4. Evaluate accuracy  
5. Use model for new predictions  

---

## 🔬 Key Insights & Reflection

🔹 **Challenges**:  
- Complex data cleaning (duplicate rows, missing data)  
- Docker setup with Airflow and NLTK  
- Switching from Twitter API to YouTube data due to API limitations  

🔹 **Lessons Learned**:  
- Importance of data cleaning for accuracy  
- Adapting hypotheses when initial data didn’t yield meaningful results  
- Collaborative teamwork is critical for success  

🔹 **Future Improvements**:  
- Improve user interface and visualizations  
- Integrate chatbot for instant health insights  
- Strengthen data security for sensitive medical information  

---

## 📈 Results

- KNN provided actionable predictions for heart disease risk.  
- Hypothesis 3: Changing to max heart rate and cholesterol levels significantly improved predictive accuracy.  

---

## 📜 References

- [Machine Learning Basics: KNN Algorithm](https://towardsdatascience.com/machine-learning-basics-with-the-k-nearest-neighbors-algorithm-6a6e71d01761)  
- [Heart Disease Prediction Using KNN & PSO](https://www.alliedacademies.org/articles/prediction-of-heart-disease-using-knearest-neighbor-and-particle-swarm-optimization.html)  
- [RStudio Implementation Example](http://rstudio-pubstatic.s3.amazonaws.com/318411_18399592759841f2a151e445adb851c7.html)  
- [YouTube Video: KNN for Heart Disease Prediction](https://www.youtube.com/watch?v=_xfCq9mxrwM&ab_channel=CodewithMarcus)  

---

**Author**: Sidharth Jain  
**Date**: 16 May 2023
