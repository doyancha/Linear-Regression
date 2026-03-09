# 🚗 📊 Linear Regression Examples

![Python](https://img.shields.io/badge/python-3.11-blue)
![Jupyter](https://img.shields.io/badge/jupyter-notebook-orange)
![License](https://img.shields.io/badge/license-MIT-green)

A collection of **three beginner-friendly linear regression projects**. Each example is contained in a Jupyter notebook and demonstrates
how to build, evaluate, and visualize a simple regression model using real CSV datasets.

---

## 📌 Projects Overview

| Notebook | Dataset | Features | Target | Description |
|----------|---------|----------|--------|-------------|
| Car Price Prediction | `car_price_dataset.csv` | `Car_Age` | `Price` | Predict used car price based on age |
| House Price Prediction | `house_price_dataset.csv` | `Size_sqft` | `Price` | Estimate house value by size (sqft) |
| Student Score Prediction | `student_score_dataset.csv` | `Hours` | `Score` | Forecast exam score from study hours |

> 📁 A helper file `linear_regression_examples.md` consolidates all the code in one place for quick copying.

---

## 🛠 Workflow (common to all notebooks)

1. **Import libraries** (`pandas`, `numpy`, `scikit-learn`, `matplotlib`).
2. **Load the CSV** and perform any necessary column renaming.
3. **Define variables**: independent (X) and dependent (y).
4. **Split** data into training and test sets (80/20).
5. **Create & train** a `LinearRegression` model.
6. **Predict** on test data and evaluate with **R² score**.
7. **Visualize** data points and the regression line.

This step-by-step flow makes understanding and modification easy, even for beginners.

---

## 🚀 Getting Started

```bash
# clone the repo
git clone https://github.com/doyancha/Linear-Regression.git
cd "Linear-Regression"

# install dependencies (use a virtual environment if preferred)
pip install pandas numpy scikit-learn matplotlib jupyter

# launch notebooks
jupyter notebook
```

Open any of the listed notebooks and run the cells sequentially to reproduce the analyses.

---

## 🎨 Customize & Extend

- Add new features (e.g. `Car_Model`, `Location`) and retrain the models.
- Replace datasets with your own CSV files; just match the column names.
- Convert notebooks into Python scripts for command‑line usage.

---

## 📝 Notes

- Datasets are small and artificial—ideal for learning, not for production use.
- Models are **simple linear regressions**; try polynomial or multiple regression
to see performance differences.

---

## 💡 Tips

- Use `pip install -r requirements.txt` if you add a requirements file later.
- Consider adding a `.gitignore` to avoid checking in large datasets or
  `.ipynb_checkpoints`.

---

Feel free to ⭐ the repo, fork it, or open an issue with questions or improvements!
