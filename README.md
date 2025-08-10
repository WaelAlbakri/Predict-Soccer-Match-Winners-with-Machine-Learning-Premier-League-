# Predict **Soccer** Match Winners with Machine Learning (Premier League)

---

## ⚽ Why I built this

I’m a big soccer fan and follow the Premier League closely. This project combines that passion with data science: I wanted to see how well I could predict match winners using careful feature engineering (rolling form), a time-aware split, and a simple, reproducible model.

---

## ✅ What I did 

1. **Loaded raw Premier League data** from `matches.csv`.
2. **Cleaned & prepared** the dataset (types, missing values, target creation).
3. Built a **baseline Random Forest** on a small set of predictors and evaluated **precision**.
4. Engineered **rolling-average features** (form, goals, shots, etc.) that use *only past matches* (no look-ahead).
5. Modeled **both sides of each match** (Team A vs Team B views + feature deltas) to capture relative strength.
6. **Retrained and re-evaluated**, improving performance step by step to **~67.5% precision** on validation.

> I optimize **precision** so that when I predict a winner, I’m right as often as possible—useful for decision contexts like picks/odds strategies.

---

Thank You!
