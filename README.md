# House Price Prediction using Linear Regression

A beginner-friendly Machine Learning project to predict house prices based on area using **Simple Linear Regression**. This project is built for learning purposes, focusing on understanding the mathematics, model evaluation, and real-world business insights.

---

## Project Structure

'''
LinearRegression/
├── dataset/
│   └── house_price_dataset.csv
├── model/
│   └── LinearRegression_house_price_prediction.ipynb
├── README.md
'''

---

##  Objective

To build a Linear Regression model that predicts house price based on the **area** (in sq.ft) of the house.

---

## Dataset

- **File**: `house_price_dataset.csv`
- **Features**: 
  - `area` (independent variable)
  - `price` (target variable)
- Contains synthetic/realistic house data for learning purposes.

---

## Technologies Used

- Python
- Pandas & NumPy
- Scikit-learn
- Matplotlib & Seaborn
- Jupyter Notebook

---

## Exploratory Data Analysis (EDA)

- Visualized the relationship between **Area** and **Price** using Scatter Plot.
- Confirmed a strong positive linear relationship.
- Performed Residual Analysis to validate Linear Regression assumptions.

---

## Model Training

- **Algorithm**: Simple Linear Regression
- **Equation**: `Price = m × Area + c`
- **Training Method**: 80% Train / 20% Test split

### Model Parameters

| Parameter         | Value      |
|-------------------|------------|
| Intercept (c)     | 1,007.14   |
| Slope (m)         | 250.00     |

**Interpretation**:
- For every **1 sq.ft increase** in area, the house price increases by **$250** on average.

---

## Model Evaluation Metrics

Intercept (c)     : 1,007.14
Slope (m)         : 250.00
R² Score (Train)  : 1.0000
R² Score (Test)   : 1.0000
RMSE              : $120.89


### Metrics Explanation:

- **R² Score = 1.0000** → The model explains **100%** of the variation in house prices using Area.
- **RMSE = $120.89** → On average, the model's prediction is off by **$120.89**.

---

## Business Insights

- On average, our prediction is off by **$121**. Area explains **99%** of the variation in house prices.

- **Example**: If the average house price is **$2000**, a **$121** error may be **acceptable for initial screening** (e.g., property listing suggestions), but **not recommended for final pricing decisions**.

- This model is best suited for **quick estimations** and understanding the core relationship between area and price.

---

## How to Use

1. Open the notebook:
   ```bash
   LinearRegression/model/LinearRegression_house_price_prediction.ipynb

## Key Learnings

- Mathematics behind Linear Regression
- Importance of EDA and Residual Analysis
- Model evaluation using MSE, RMSE, and R²
- Train-Test splitting and avoiding data leakage
- Converting model output into business insights

## Author
Navaneethan K

navaneethan1810@gmail.com
