# California Housing Price Prediction

## Overview

This folder (`data/`) contains the **California Housing** dataset.  
The goal is to apply linear regression + statistical & pattern recognition concepts covered in class (CLT, correlation, bias-variance, etc.) to predict the median house value in Californian districts.

---

## Dataset

- **Name:** California Housing (scikit-learn) :contentReference[oaicite:0]{index=0}  
- **Number of samples:** 20,640  
- **Number of features:** 8 numeric attributes:  
  `MedInc`, `HouseAge`, `AveRooms`, `AveBedrms`, `Population`, `AveOccup`, `Latitude`, `Longitude`  
- **Target:** `MedHouseVal` — median house value of district (in units of \$100,000)  
- **No missing values**; all features are continuous/real numbers.  

---

## Objectives

This work demonstrates:

1. Exploratory Data Analysis (EDA): understanding feature distributions, relationships, correlations.  
2. Central Limit Theorem (CLT) demo: sampling distributions of the target.  
3. Linear Regression: modeling, performance evaluation (RMSE, R²).  
4. Cross-validation to estimate generalization performance.  
5. Bias-Variance trade-off: via learning curves.  
6. Residual analysis & error inspection.  
7. Interpretation of results and discussion of limitations & possible improvements.

---

## Code & Files

| File | Description |
|---|-------------|
| `model.ipynb` | Jupyter notebook with full code: data loading, EDA, model training & evaluation, plots |
| `data/california_housing.csv` | The dataset saved locally (csv) for reproducibility |
| `plots/` | Saved figures/plots (histograms, heatmaps, scatter plots, CLT, residuals, learning curve etc.) |
| `README.md` | This file: explains structure, how to run, and what results to expect |

---

## How to Run

1. Ensure you have Python 3.x installed (≥ 3.8 recommended).  
2. Install required packages:

   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn
