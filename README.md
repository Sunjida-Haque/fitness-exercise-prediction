# 🏃‍♀️ Fitness Exercise Prediction using Machine Learning

This project was developed as part of a machine learning course to explore how predictive models can enhance personal fitness tracking. Using historical workout data, we built models to predict users’ **next exercise type**, **start time**, and **duration** — enabling smart recommendations for future workouts.

---

## 🎯 Objective

To apply machine learning techniques for:
- 🧠 Predicting the next exercise category (classification)
- ⏱️ Estimating time and duration of the next activity (regression)

Our goal was to help improve fitness routines through intelligent suggestions based on a user's previous workout patterns.

---

## 🛠️ Tools & Libraries

- Python (Jupyter Notebook)
- `pandas`, `seaborn`, `matplotlib`
- `sklearn`: Random Forest, Linear Regression, GridSearchCV
- Real workout data (JSON format)

---

## 📊 Methodology

1. **Data Collection**  
   Parsed hundreds of workout records stored in JSON format, ranging from walking, weight training, skiing, to swimming.

2. **Data Cleaning & Preparation**  
   - Standardized inconsistent entries
   - Extracted relevant fields (e.g., activity type, start time, distance, duration)

3. **Exploratory Data Analysis**  
   - Analyzed trends in frequency, duration, and types of workouts
   - Visualized workout patterns over time

4. **Feature Engineering & Modeling**  
   - Encoded exercise categories
   - Used Random Forest for classification (exercise type)
   - Used Polynomial Regression for predicting time & duration

5. **Model Evaluation**  
   - Classification accuracy score
   - Regression: R² and Mean Squared Error

---

## 🧠 Key Learnings

- Managing and preprocessing real-world JSON fitness tracking data
- Combining both classification and regression in one analysis
- Model tuning using GridSearchCV for better accuracy
- Importance of feature selection in real-life tracking data

---

## 👤 Author

**Sunjida Haque**  
LUT University

---

## 📎 Files

- `fitness_exercise_prediction_model.ipynb`: Main analysis code
- `fitness_exercise_prediction_mode.pdf`: Final report
- `fitness_exercise_prediction_model.html`: Rendered HTML version of notebook

---

## 🔗 Repository Link

To view the full notebook and model walkthrough, visit:  
👉 **[GitHub Repo](https://github.com/Sunjida-Haque/fitness-exercise-prediction)** 
