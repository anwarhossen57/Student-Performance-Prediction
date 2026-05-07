# 🎓 Student Performance Prediction using Machine Learning

## 📌 Project Overview
This project predicts a student's overall academic performance based on demographic, social, and economic factors.

Using Exploratory Data Analysis (EDA) and Random Forest Regression, this project identifies how external factors such as parental education, lunch type, and test preparation courses impact student performance.

The model predicts a student's average academic score by analyzing patterns from historical student data.

---

## 🎯 Objectives
- Analyze student performance data
- Identify factors affecting academic success
- Build a machine learning prediction model
- Visualize important insights from the dataset

---

## 🛠️ Tech Stack & Libraries
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

---

## 📂 Dataset
**StudentsPerformance.csv**

Dataset features:
- Gender
- Race/Ethnicity
- Parental Level of Education
- Lunch Type
- Test Preparation Course
- Math Score
- Reading Score
- Writing Score

---

## ⚙️ Project Workflow

### 1. Data Cleaning
- Checked missing values
- Removed duplicates
- Ensured clean dataset

### 2. Feature Engineering
Created a new feature:

average_score = (math score + reading score + writing score) / 3

### 3. Data Preprocessing
- Applied Label Encoding on categorical data
- Prepared dataset for model training

### 4. Exploratory Data Analysis (EDA)
- Score distribution analysis
- Parental education impact analysis
- Lunch type comparison
- Test preparation analysis
- Gender comparison

### 5. Model Building
Implemented:
- Random Forest Regressor

### 6. Feature Importance Analysis
Identified the most important factors affecting student performance.

---

## 📈 Key Insights
- Parental education has a strong impact on student performance
- Students with standard lunch performed better
- Test preparation course completion improved scores
- Gender had relatively lower impact compared to environmental factors

---

## 📁 Repository Structure
```bash
├── StudentsPerformance.csv
├── Student_Performance_Prediction.ipynb
└── README.md
```

---

## 🚀 How to Run
1. Clone this repository
2. Open Google Colab
3. Upload the notebook file
4. Upload the dataset
5. Run all cells

---

## 🔮 Future Improvements
- Try multiple ML models
- Hyperparameter tuning
- Model deployment
- Improve accuracy

---

## ⭐ Give this repository a star if you found it useful!
