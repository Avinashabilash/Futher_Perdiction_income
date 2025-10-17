# 💰 Canada Per Capita Income Prediction

## 🧠 Description
This project predicts **Canada’s per capita income** using a **Linear Regression model**.  
By analyzing historical income data, the model learns the relationship between **year** and **income** and predicts future income trends.  
Visualization and regression analysis help to understand how the country's economy evolved over time.

---

## 🎯 AIM
To build a **machine learning model** that can accurately predict **per capita income** for a given year using **Linear Regression**.

---

## 🧩 Goals
- Predict **per capita income** based on the year.  
- Visualize the growth trend using a scatter plot and regression line.  
- Understand how income changes over time.  
- Make future income predictions for upcoming years.  

---

## ⚙️ Technical Details
**Language & Libraries:**  
- Python  
- pandas  
- numpy  
- scikit-learn  
- matplotlib  

---

## 🧾 Data Preprocessing
- Load the dataset using `pandas`.  
- Extract relevant features: `year` and `per capita income (US$)`.  
- Visualize the dataset for trend analysis.  

---

## 🧮 Model Used
**Linear Regression**  
- Formula: `y = m * x + c`  
- `y` = per capita income  
- `x` = year  
- `m` = slope (growth rate)  
- `c` = intercept  

---

## 💻 Code Implementation

```python
# Import libraries
import pandas as pd
import numpy as np
from sklearn import linear_model
import matplotlib.pyplot as plt

| Year | Predicted Per Capita Income (US$) |
| ---- | --------------------------------- |
| 2020 | 41,288.69                         |

📋 Observation

The model captures the upward trend in Canada’s per capita income over time.

Prediction for 2020: ≈ $41,288.69

Indicates consistent economic growth over the decades.

The model can be used to forecast future income values with reasonable accuracy.
