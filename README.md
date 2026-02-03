# Melbourne House Price Project

This project predicts Melbourne house prices using a Machine Learning pipeline in Python.

## Libraries Used
- pandas
- numpy
- scikit-learn

## Steps Done
- Removed rows with missing Price
- Train-test split
- Numerical preprocessing: median imputation
- Categorical preprocessing: most frequent imputation + OneHotEncoder
- Model: Linear Regression
- Metrics: MAE, RMSE, R2

## Output
After running the notebook, it prints:
- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R2 Score

## How to Run
1. Open the notebook `melbourne-house-price-prediction.ipynb`
2. Run all cells

## Dataset
CSV file is inside:
`data_link2/Melbourne_housing_FULL.csv`

## Folder Structure

Melbourne_house_price_project/
│── melbourne-house-price-prediction.ipynb
│── README.md
└── data_link2/
└── Melbourne_housing_FULL.csv

## Future Improvements (Optional)
- Try Ridge / Lasso Regression
- Add EDA graphs and feature analysis
- Remove outliers and improve performance