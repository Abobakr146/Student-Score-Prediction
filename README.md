# Student Score Prediction

A machine learning project that predicts student exam scores using Linear and Polynomial Regression models.

## 🎯 Overview

This project analyzes student performance data to predict exam scores based on study hours, attendance, previous scores, and other factors. It compares linear vs polynomial regression to capture non-linear relationships in educational data.

## 📊 Dataset

Uses `StudentPerformanceFactors.csv` with features:
- Hours_Studied
- Attendance  
- Previous_Scores
- Exam_Score (target)

## 🚀 Quick Start

```bash
git clone https://github.com/yourusername/student-score-prediction.git
cd student-score-prediction
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
jupyter notebook Student_Score_Prediction.ipynb
```

## 📈 Results

- **Polynomial Regression** outperforms Linear Regression
- Captures non-linear relationships between study time and performance
- Shows accelerating returns in learning patterns

## 🛠️ Tech Stack

Python | Pandas | Scikit-learn | Matplotlib | Seaborn

## 📁 Files

```
├── Student_Score_Prediction.ipynb    # Main notebook
├── StudentPerformanceFactors.csv     # Dataset  
└── README.md                         # Documentation
```

## 🔍 Key Insights

- Study hours show quadratic relationship with exam scores
- Multiple features improve prediction accuracy
- Polynomial models better capture educational patterns
- Useful for identifying at-risk students and study optimization
