# Amazon Pricing & Reviews Analysis

This project analyzes Amazon ecommerce customer data to understand pricing, purchasing patterns, and review relationships. It uses machine learning models to predict total purchase amounts and explores feature correlations.

## Features

- **Data Cleaning:** Removes unnecessary columns and handles missing values.
- **Feature Engineering:** Extracts time-based features from purchase dates and applies one-hot encoding to categorical variables.
- **Exploratory Data Analysis:** Visualizes feature correlations and distributions.
- **Modeling:** Trains and tunes RandomForestRegressor and XGBRegressor models to predict purchase amounts.
- **Evaluation:** Reports RMSE and R² metrics, and visualizes predictions vs actual values.
- **Model Saving:** Exports trained models for future use.

## Project Structure

```
amazon-pricing-reviews-analysis/
├── notebooks/
│   └── amazon-pricing-reviews-analysis.ipynb
├── dataset/
│   └── ecommerce_customer_data.csv
├── random_forest_model.pkl
├── XGBRegressor_model.pkl
└── README.md
```

## Usage

1. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

2. **Run the notebook:**
    - Open `notebooks/amazon-pricing-reviews-analysis.ipynb` in Jupyter or VS Code.
    - Step through the cells to clean data, visualize, train models, and evaluate results.

3. **Dataset:**
    - Place your `ecommerce_customer_data.csv` file in the `dataset/` folder.

## Models

- **RandomForestRegressor:** Used for regression with hyperparameter tuning via GridSearchCV.
- **XGBRegressor:** Gradient boosting regression with extensive hyperparameter search.

## Outputs

- Trained models saved as `random_forest_model.pkl` and `XGBRegressor_model.pkl`.
- Visualizations of feature correlations and model predictions.

## License

This project is for educational and research purposes.