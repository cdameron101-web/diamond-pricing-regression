# Diamond Pricing Regression — Blacksheep Labs

## Project Overview

This machine learning project predicts diamond prices using multiple linear regression. It demonstrates how Python and Scikit-learn can be used to analyze data, train regression models, and evaluate prediction performance.

## Technologies Used

- Python
- Pandas and NumPy
- Scikit-learn
- Matplotlib and Seaborn
- Google Colab

## Dataset

Seaborn Diamonds Dataset

Features used:
- Carat
- Cut
- Color
- Clarity

Target variable: Diamond price (USD)

## Machine Learning Workflow

1. Loaded and explored the diamond dataset.
2. Performed exploratory data analysis.
3. Built a simple linear regression model using carat.
4. Encoded categorical variables using dummy variables.
5. Built multiple linear regression models.
6. Split the dataset into training and testing sets.
7. Evaluated model performance using MAE, MSE, RMSE, and R².
8. Compared training and testing performance to check for signs of overfitting.
9. Visualized actual versus predicted prices.

## Model Performance

| Metric | Result |
|---|---:|
| Training R² | 0.9161 |
| Testing R² | 0.9153 |
| Training MAE | $805.79 |
| Testing MAE | $802.12 |
| Testing RMSE | $1,160.32 |

The final model explains approximately 91.53% of the variation in diamond prices on the test dataset. Similar training and testing performance suggests encouraging generalization on this data split.

## Key Takeaways

- Adding relevant categorical features improved regression performance.
- Dummy variable encoding allowed categorical features to be used in linear regression.
- Comparing training and testing metrics helped assess generalization.
- Model evaluation is essential before using predictions for business decisions.

## Notebook

[View the Diamond Pricing Regression Notebook](Diamond_Pricing_Regression.ipynb)

## Author

**Blacksheep Labs**

Machine Learning | Python | Data Analytics
