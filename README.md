# ML-_football_prediction
# Football Flop Predictor ⚽🧠

Can data science help us avoid bad signings?

This project uses machine learning to predict whether a football player is likely to **flop or shine** after joining a club. By analyzing player attributes such as pace, shooting, passing, and more, we aim to assist scouts and clubs in making smarter transfer decisions.

---

## 📊 Dataset Overview

The dataset includes player ratings and metadata for male and female footballers, with the following columns:

- Player Info: `player_name`, `age`, `gender`, `club`, `league`, `nationality`, `position`, `preferred_foot`
- Physical Stats: `height_(in cm)`, `weight_(in kg)`
- Ratings: `ovr`, `pac`, `sho`, `pas`, `dri`, `def`, `phy` and their `+/-` variations

---

## 🛠 What We Did

- ✅ Loaded and cleaned player data in PostgreSQL
- ✅ Grouped players by club, gender, and league
- ✅ Created a new ML target: **Flop or Shine**
- ✅ Engineered features like average rating growth, positional fit, and physical attributes
- ✅ Trained ML models: Random Forest, XGBoost
- ✅ Evaluated performance using Accuracy, F1 Score, ROC AUC

---

## 🧪 Machine Learning Models

- Binary classification (Flop vs Shine)
- Feature importance: which stats matter most?
- Exploratory Data Analysis (EDA) on clubs and positions

---

## 📁 Folder Structure

