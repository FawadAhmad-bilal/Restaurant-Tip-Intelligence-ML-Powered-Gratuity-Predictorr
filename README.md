## 🧠 Overview
An end-to-end machine learning project that predicts restaurant tip amounts
based on customer and transaction data. This project explores multiple
regression models, compares their performance, and visualizes predictions
to derive actionable insights from real-world dining behavior.

---

## 📊 Dataset
- **Source:** Seaborn built-in Tips dataset
- **Rows:** 244 records
- **Features:** total_bill, sex, smoker, day, time, size
- **Target:** tip (in USD)

---

## ⚙️ Project Pipeline

| Step | Description |
|------|-------------|
| 01 | Data Loading & Exploration |
| 02 | Null Value Check & EDA |
| 03 | Feature Encoding (Label & One-Hot) |
| 04 | Train/Test Split (80/20) |
| 05 | Model Training & Comparison |
| 06 | Evaluation (R², RMSE) |
| 07 | Actual vs Predicted Visualization |

---

## 🤖 Models Compared

| Model | R² Score |
|-------|----------|
| Random Forest | 0.34 |
| Linear Regression | 0.47 |
| Ridge Regression | 0.47 |
| Lasso Regression | 0.55 ✅ Best |

---

## 💡 Key Findings
- `total_bill` is the strongest predictor of tip amount
- Lasso Regression outperformed all other models by automatically
  eliminating irrelevant features
- Human tipping behavior is inherently random — limiting model ceiling to ~0.55

---

## 🧰 Tech Stack
![Python](https://img.shields.io/badge/Python-3.13-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-green)

- Python 3.13
- Pandas & NumPy
- Scikit-learn
- Matplotlib & Seaborn

---

## 🚀 How to Run
```bash
# Clone the repository
git clone https://github.com/yourusername/restaurant-tip-predictor

# Open notebook
jupyter notebook Random_forest_Regression.ipynb
```

---

## 📁 Project Structure
