#  🤖 AI Job Market Trends Analysis & Prediction (ML Project)

##  📌 Project Overview

This project focuses on analyzing AI Job Market Trends (2026 dataset) and building multiple Machine Learning models to understand and predict job-related outcomes.

The project covers:

**Regression** → Predicting Salary

**Classification** → Predicting Hiring Urgency

It also helps in identifying market demand, skill trends, and job patterns using data analysis.

## 🎯 Objectives

- Understand AI job market dataset
- Perform data cleaning and preprocessing
- Analyze job trends using EDA
- Build multiple Machine Learning models
- Evaluate and compare model performance
- Predict salary and hiring urgency


# 🤖 Machine Learning Algorithms Used 

## 1️⃣ Linear Regression

- Used for predicting continuous values (Salary)
- Assumes linear relationship between features and target
- Simple and easy to interpret model

  
## 2️⃣ Logistic Regression

- Used for classification (Hiring Urgency)
- Outputs categories:
             Low / Medium → 0
             High → 1 / 2
- Uses sigmoid function for prediction


## 3️⃣ Random Forest Classifier 🌳

- Ensemble learning algorithm (multiple decision trees)
- Handles non-linear relationships
- Reduces overfitting
- Provides high accuracy

  
## 4️⃣ Support Vector Machine (SVM)

- Used for classification problems
- Creates optimal decision boundary (hyperplane)
- Works well with high-dimensional data
- Requires feature scaling

  
## 🧰 Technologies & Libraries Used

- Python – Programming language
- NumPy – Numerical operations
- Pandas – Data manipulation
- Matplotlib / Seaborn – Data visualization
- Scikit-learn – Machine Learning models
- Jupyter Notebook – Development environment

  
## 🔄 Project Workflow

Data Collection
      ↓
Data Cleaning & Preprocessing
      ↓
Exploratory Data Analysis (EDA)
      ↓
Feature Engineering
      ↓
Train–Test Split
      ↓
Model Training
      ↓
Model Evaluation
      ↓
Prediction


## 🧹 Data Preprocessing

- Checked missing values using isnull()
- Removed duplicate data
- Converted categorical data into numerical:
- Job Role
- Company Size
- Experience Level
- Education Level
- Hiring Urgency

# 👉 Machine Learning models require numerical input data.

# 📊 Exploratory Data Analysis (EDA
)
Key Analysis Performed:
- Correlation heatmap
- Salary vs Experience analysis
- Job role distribution
- Skill demand analysis
- Monthly & yearly job trends
- Pairplot relationships
Insights:
- Salary increases with experience
- Python, ML, and Cloud skills are highly demanded
- Data Science roles have high job openings
- Hiring trends vary over time

  
## 📏 Evaluation Metrics 

- Regression (Salary Prediction)
- R² Score – Model performance
- Mean Squared Error (MSE) – Error measurement
- Classification (Hiring Urgency)
- Accuracy – Correct predictions
- Confusion Matrix – Detailed classification results

  
## 📊 Results

- Linear Regression works well for salary prediction
- Random Forest provides higher accuracy in classification
- Logistic Regression is a good baseline model
- SVM performs well for complex decision boundaries

  
## 🧠 Key Learnings

- Feature engineering is very important
- Feature scaling improves model performance
- Using multiple models helps in comparison
- EDA helps understand hidden patterns

  
## 🏁 Conclusion

This project demonstrates:

- End-to-End Machine Learning workflow
- Real-world dataset analysis
- Multiple ML model comparison
