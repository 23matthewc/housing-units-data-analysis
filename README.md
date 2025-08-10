# California Housing Analysis

Linear regression analysis of California housing block data from the US Census to predict median house values. Includes variable standardization, predictor evaluation, and multiple regression modeling.

---

## Project Overview

This project analyzes housing data from over 20,000 California housing blocks using linear regression methods. The goal is to predict the median house value in each block based on seven predictor variables, including housing age, number of rooms, bedrooms, population, households, income, and proximity to the ocean.

The analysis involves standardizing relevant predictors, evaluating their individual and combined predictive power, and assessing potential issues such as collinearity among variables.

---

## Dataset

The dataset `housingUnits.csv` contains the following columns (per row = one housing block):

1. Median age of the houses in the block (years)  
2. Total number of rooms  
3. Number of bedrooms  
4. Population  
5. Number of households  
6. Median household income (thousands of dollars)  
7. Proximity to the ocean (0 = closest, 4 = farthest)  
8. Median house value (dollars) — Outcome variable

---

## Methods

- Data loading and exploratory analysis (including histograms and scatter plots)  
- Standardization of predictor variables 2 and 3 by either population or households to account for varying block sizes  
- Simple linear regression for each predictor to evaluate predictive power  
- Multiple linear regression combining all predictors  
- Investigation of collinearity among variables 2, 3, 4, and 5  
- Interpretation of regression coefficients, R² values, and visualizations

---

## How to Run

1. Clone the repo:  
   ```bash
   git clone <repo-url>
