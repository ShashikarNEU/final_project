# Population Data Analysis — Predictive Modeling & EDA

A data science project analyzing global population trends using regression modeling, exploratory data analysis (EDA), and visualization. Built with Python in Jupyter notebooks, this project uncovers insights into how fertility rates, median age, and life expectancy influence population growth — and builds predictive models to forecast future trends.

---

## Project Overview

Global population dynamics are shifting dramatically. This project dives into multi-country, multi-decade population data to answer key questions:

- How do fertility rates correlate with population growth?
- Which regression technique best predicts population trends?
- What demographic shifts are occurring across different regions?

---

## Features

- **Exploratory Data Analysis (EDA)** — Distribution plots, correlation matrices, trend lines across countries and years
- **Data Cleaning** — Handling missing values, normalizing country names, merging datasets across multiple CSV sources
- **Feature Engineering** — Derived variables from fertility rate, median age, and life expectancy
- **Regression Modeling** — Comparison of LARS, Lasso, and Ridge regression for population forecasting
- **Model Evaluation** — Error metrics (RMSE, MAE, R²) to select the best-performing model
- **Visualization** — Rich plots uncovering demographic shifts and declining fertility trends

---

## Datasets

| File | Description |
|------|-------------|
| `data/population.csv` | Population figures by country and year |
| `data/median-age-vs-births-per-woman.csv` | Median age and fertility rate by country |
| `data/life-expectancy.csv` | Life expectancy data by country and year |
| `data/population-by-age-group.csv` | Population broken down by age group |

Data sourced from publicly available global demographic datasets (Our World in Data).

---

## Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3.x | Core language |
| Jupyter Notebook | Interactive analysis environment |
| Pandas | Data loading, cleaning, and manipulation |
| NumPy | Numerical operations |
| Matplotlib / Seaborn | Data visualization |
| Scikit-learn | Regression models and evaluation metrics |

---

## Notebooks

| Notebook | Description |
|----------|-------------|
| `population.ipynb` | Main analysis: EDA, feature engineering, modeling, and evaluation |

---

## Key Findings

- **Declining Fertility Rates** — Most developed nations show a consistent decline in births per woman over the past 50 years
- **Aging Populations** — Median age is rising globally, with significant implications for workforce and healthcare policy
- **Ridge Regression** performed best among the tested models, balancing bias and variance on this dataset
- **Life expectancy** and **fertility rate** are the strongest predictors of population trajectory

---

## Getting Started

### Prerequisites

- Python 3.8+
- Jupyter Notebook or JupyterLab

### 1. Clone the Repository

```bash
git clone https://github.com/ShashikarNEU/final_project.git
cd final_project
```

### 2. Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 3. Launch Jupyter

```bash
jupyter notebook
```

Open `population.ipynb` to run the full analysis.

---

## License

This project is licensed under the MIT License.
