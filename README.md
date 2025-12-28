# Day 01 — Linear Regressor: SyntheticForge
A foundational machine learning project demonstrating **Simple Linear Regression** using a custom synthetic dataset.  
This project simulates real-world behavior by introducing random noise to a predictable linear relationship and evaluating how well the model learns the underlying pattern.

The target function used to generate data:
\[
y = 3x + 4 + \{noise}
\]

---

## 🚀 Objectives
- Generate a synthetic regression dataset
- Perform exploratory data analysis (EDA)
- Train and evaluate a Linear Regression model
- Visualize regression fit and residual behavior
- Interpret error metrics and model parameters

---

## 📁 Project Structure
```text
Day-01-Linear-Regressor-SyntheticForge/
├─ data/
│  └─ synthetic_data.csv
├─ models/
│  └─ linear_regressor_syntheticforge.pkl
├─ notebooks/
│  └─ Day-01-Linear-Regressor-SyntheticForge.ipynb
└─ README.md
```

---

## 📦 Dataset Information
| Detail | Description |
|--------|--------------|
| Type | Synthetic numeric dataset |
| Size | 200 samples |
| Features | Feature_X (input), Target_y (output) |
| File | `data/synthetic_data.csv` |
| Generation Formula | `y = 3x + 4 + noise` |

Dataset is created automatically in the notebook – no external download required.

---

## 🧠 Tools & Libraries Used
| Category | Tools |
|----------|-------|
| Language | Python |
| Notebook Environment | Jupyter Notebook |
| Data Processing | NumPy, Pandas |
| Visualization | Matplotlib, Seaborn |
| Model & Evaluation | Scikit-Learn (LinearRegression) |

---

## 📊 Model Performance Metrics
| Metric | Purpose |
|--------|----------|
| MSE | Measures squared error between predictions and actual values |
| MAE | Measures average prediction error |
| R² Score | Explains variance captured by the model (closer to 1 is better) |

Residual and regression-fit plots are included for diagnostic insights.

---

## 📈 Visualizations Included
- Scatter plot of original dataset
- Regression line overlay on test predictions
- Actual vs Predicted comparison table
- Residual error plot

These help validate whether the model is capturing the trend and where it struggles.

---

## ▶️ Run This Project
```bash
# Clone the repository
git clone https://github.com/USERNAME/Day-01-Linear-Regressor-SyntheticForge.git
cd Day-01-Linear-Regressor-SyntheticForge

# Launch the notebook
jupyter notebook notebooks/Day-01-Linear-Regressor-SyntheticForge.ipynb
```

---

## 💾 Model Saving
The trained model is exported for reuse:
```
models/linear_regressor_syntheticforge.pkl
```

This can be loaded later for predictions or integrated into an API.

---

## 📝 Key Learnings
- How linear regression finds slope & intercept
- Impact of randomness on predictive accuracy
- Why residual analysis matters
- Interpreting metrics beyond accuracy

---

## 📌 License
This project is free to use, improve, and build upon for educational or portfolio purposes.
