# Calories Burnt Prediction using Machine Learning

**Project Inspired By**: *Project 16. Calories Burnt Prediction using Machine Learning with Python*  
**YouTube Tutorial**: https://youtu.be/ZD27QTvSbTY

---

## Overview
This project aims to build a machine learning model that predicts the number of calories burned during exercise. Using features such as age, gender, height, weight, duration of exercise, heart rate, and body temperature, the model estimates calorie expenditure to support fitness and health tracking.

---

## Dataset
- **Source**: Dataset typically comprises two CSV files—`exercise.csv` and `calories.csv`, containing user and calories data respectively.
- **Structure**: After merging based on a `User_ID`, the dataset includes features along with the target variable `Calories`.

---

## Project Structure

```
├── data/
│   ├── calories.csv
│   └── exercise.csv
├── notebooks/
│   └── Calories_Burnt_Prediction.ipynb
├── src/
│   ├── train_model.py      # Script to train and evaluate ML models
│   └── app.py              # (Optional) Web app interface (e.g., with Streamlit or FastAPI)
├── requirements.txt        # Required Python packages
└── README.md               # This file
```

---

## Dependencies
Install all dependencies via:

```bash
pip install -r requirements.txt
```

Common dependencies include:
- `numpy`, `pandas`, `scikit-learn`, `xgboost`, `matplotlib`, `seaborn`
- Optional (for deployment): `streamlit` or `fastapi`, `uvicorn`

---

## Getting Started
1. **Explore the data** using the Jupyter notebook:
   - Merge datasets (`exercise.csv`, `calories.csv`)
   - Perform exploratory data analysis (EDA)
   - Visualize relationships (e.g., scatter plots, correlation heatmaps)
2. **Train models** such as:
   - Linear Regression
   - Decision Tree Regressor
   - Random Forest Regressor
   - XGBoost Regressor

