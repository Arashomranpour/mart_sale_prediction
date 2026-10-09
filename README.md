<div align="center">

# 🏬 Big Mart Sales Prediction

**Regression models that forecast product sales for retail outlets, combined into a stacked ensemble.**

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7)
![CatBoost](https://img.shields.io/badge/CatBoost-FFCC00?logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)

</div>

---

## ✨ Overview

`i.ipynb` works on `Train.csv` (item and outlet attributes → sales):

- 🧹 Data cleaning and EDA with pandas, Seaborn and Matplotlib.
- 🏷️ Categorical features handled with a `ColumnTransformer`: `Item_Identifier`, `Item_Fat_Content`, `Item_Type`, `Outlet_Identifier`, `Outlet_Size`, `Outlet_Location_Type`, `Outlet_Type`.
- 🤖 Models compared: **Linear Regression, Linear SVR, Gradient Boosting, XGBoost, CatBoost**.
- 🧱 A **`StackingRegressor`** combines them into the final predictor.

## 🚀 Getting Started

```bash
git clone https://github.com/Arashomranpour/mart_sale_prediction.git
cd mart_sale_prediction
pip install pandas numpy matplotlib seaborn scikit-learn xgboost catboost jupyter
jupyter notebook i.ipynb
```

## 📁 Project Structure

```
.
├── i.ipynb      # EDA, preprocessing, models, stacking
└── Train.csv    # Dataset
```

## 🛠️ Tech Stack

`scikit-learn` · `XGBoost` · `CatBoost` · `pandas` · `Seaborn`
