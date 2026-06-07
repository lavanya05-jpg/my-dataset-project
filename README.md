# 🚦 Traffic Demand Prediction

Predicting traffic demand at urban locations using machine learning — built for the HackerEarth ML Challenge.

---

## 📌 Problem Statement

Predict traffic demand at various urban locations using location, road, and weather features.

---

## 📊 Dataset

| Split | Rows | Columns |
|-------|------|---------|
| Train | 77,299 | 11 |
| Test | 41,778 | 10 |

**Source:** [HackerEarth Machine Learning Challenge](https://www.hackerearth.com)

---

## 🔧 Features Used

| Feature | Description |
|---------|-------------|
| `Geohash` | Location encoding |
| `Day` | Day of the week |
| `Timestamp` | Time of the day |
| `Road Type` | Type of road |
| `Number of Lanes` | Lane count on the road |
| `Large Vehicles Allowed` | Whether large vehicles are permitted |
| `Landmarks Nearby` | Presence of nearby landmarks |
| `Temperature` | Temperature at the location |
| `Weather` | Weather condition (Sunny, Rainy, Foggy, Snowy) |

---

## 🤖 Approach

1. **Exploratory Data Analysis (EDA)** — Understanding distributions, correlations, and patterns
2. **Feature Engineering** — Encoding, transformations, and new feature creation
3. **Model Training & Evaluation** — Training ML models and tuning hyperparameters
4. **Metric:** R² Score

---

## 📁 Project Structure

```
├── dataset/
│   ├── train.csv               # Training data (77,299 rows)
│   ├── test.csv                # Test data (41,778 rows)
│   └── sample_submission.csv   # Submission format
├── notebook.ipynb              # Main analysis and model code
├── submission.csv              # Final predictions
└── README.md
```

---

## 🏆 Platform

**HackerEarth** — Traffic Demand Prediction Challenge

---

## 👩‍💻 Author

**Lavanya** — [GitHub](https://github.com/lavanya05-jpg)
