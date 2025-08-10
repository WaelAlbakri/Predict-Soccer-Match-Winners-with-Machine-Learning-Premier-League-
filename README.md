# Predict **Soccer** Match Winners with Machine Learning (Premier League)

---

## ⚽ Why I Built This

As a passionate soccer fan, especially of the **Premier League**, I wanted to combine my love for the sport with my interest in ML and data science. This project explores how machine learning can be applied to predict match winners by leveraging historical match data, rolling performance metrics, and a time-aware modeling approach.

---

## 📋 Project Overview

This project takes raw Premier League match data, cleans it, engineers predictive features, and trains a **Random Forest** model to forecast match winners. The primary evaluation metric is **precision**, as I value making accurate predictions when I choose a winner rather than predicting every possible outcome.

---

## ✅ Steps I Took

1. **Data Loading**  
   Imported raw Premier League match data from `matches.csv`.

2. **Data Cleaning & Preparation**  
   - Fixed data types  
   - Handled missing values  
   - Created the target variable for predicting winners

3. **Baseline Model**  
   Trained an initial **Random Forest** classifier using a small set of predictors.

4. **Feature Engineering**  
   - Added **rolling-average features** (e.g., form, goals, shots)  
   - Ensured no data leakage by using only past matches for feature calculations

5. **Both-Sides Match Modeling**  
   Generated features for both teams in a match, including performance deltas, to better capture relative strength.

6. **Model Retraining & Evaluation**  
   Iteratively retrained and evaluated the model, ultimately reaching **~67.5% precision** on the validation set.

> **Why Precision?**  
> Precision was selected as the primary metric to emphasize the accuracy of positive predictions. The goal was to ensure that when the model predicts a specific team to win, that prediction is correct as often as possible, aligning with practical decision-making scenarios.

---

Thank You!
