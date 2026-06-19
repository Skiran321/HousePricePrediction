# House Price Prediction


Built a regression model to predict house prices using the [Housing Prices Dataset](https://www.kaggle.com/datasets/yasserh/housing-prices-dataset) from Kaggle (545 rows, 13 columns). Cleaned the data, trained Linear Regression and Random Forest models, compared their performance, and visualized the results.

## Results

| Model | MAE | RMSE | R² Score |
|---|---|---|---|
| Linear Regression | 9,70,043 | 13,24,507 | 0.653 |
| Random Forest | 10,21,546 | 14,00,566 | 0.612 |

Area, number of bathrooms, and air conditioning turned out to be the strongest predictors of price.

## Files

- `analysis.ipynb` — full notebook (data cleaning, models, charts, insights)
- `Housing.csv` — dataset
- `summary.pdf` — 1-page summary
- `charts/` — saved chart images

## Tools

Python, Pandas, Scikit-learn, Matplotlib, Seaborn
