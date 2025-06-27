# 📊 Student Marks Predictor – Machine Learning Project

This project is a simple **Linear Regression** implementation to predict a student's marks based on the number of hours they studied. It's an excellent beginner-level project to understand the complete ML workflow: data analysis, model training, prediction, and evaluation.

---

## 🚀 Project Overview

**Goal**: Build a machine learning model to predict student exam scores based on study hours using Linear Regression.

**Problem Statement**:  
Given a dataset containing hours studied vs scores obtained, train a model to predict the likely score based on input hours.

---

## 🧠 Technologies Used

- **Python**
- **Pandas** – Data handling
- **Matplotlib & Seaborn** – Visualization
- **scikit-learn** – Model training & evaluation

---

## 📁 Dataset

- **Source**: [Supervised ML Task – The Sparks Foundation](http://bit.ly/w-data)
- **Columns**:
  - `Hours` – Hours studied
  - `Scores` – Marks scored

---

## 🔍 Workflow

1. Load and explore the dataset
2. Visualize data using scatter plot
3. Prepare the data (features and labels)
4. Split data into training and test sets
5. Train Linear Regression model
6. Predict on test data
7. Evaluate model using MSE and R² Score
8. Visualize the regression line

---

## 📈 Results

- ✅ Model trained successfully on the dataset
- 📉 Mean Squared Error: *[add your value here]*
- 📊 R² Score: *[add your value here]*

---

## 📌 Example Prediction

> Predict score if a student studies 9.25 hours:

```python
hours = [[9.25]]
predicted_score = model.predict(hours)
print(predicted_score)
