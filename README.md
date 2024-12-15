# Daily Sales Prediction and Inventory Optimization Project

This project leverages machine learning techniques to predict daily sales and optimize inventory planning for various products, providing actionable insights for procurement decisions.

## Project Features

- **Data Integration**: Combines multiple datasets, including product and sales data, for comprehensive analysis.
- **Model Comparisons**: Implements and evaluates multiple predictive models (e.g., Linear Regression, Random Forest) to determine the best-performing algorithm.
- **Feature Analysis**: Identifies key factors affecting sales, such as weather and product categories, using feature importance analysis.
- **Error Minimization**: Compares metrics like Mean Absolute Error (MAE) and Root Mean Square Error (RMSE) to assess model performance and improvements.
- **Residual Analysis**: Evaluates residual distributions to ensure prediction accuracy and reliability.
- **Inventory Planning**: Aligns predictive insights with procurement strategies, optimizing stock levels for individual products.

## Key Results

1. **Linear Regression**:
   - R²: 0.918
   - MAE: 87.89
   - RMSE: 110.36
   - Insights: High predictive power but significant prediction errors in MAE and RMSE.

2. **Random Forest Model**:
   - Best Parameters: `{'max_depth': 10, 'max_features': None, 'n_estimators': 600}`
   - R² (Test): 0.9955
   - MAE (Test): 18.18
   - RMSE (Test): 25.91
   - Improvement: ~79.3% reduction in MAE and ~76.5% reduction in RMSE compared to Linear Regression.

## Visualizations

- Residual distributions
- Predicted vs. actual sales
- Feature importance rankings

## Conclusion

The Random Forest model significantly outperforms Linear Regression in reducing prediction error and increasing accuracy. Its predictions provide a reliable basis for:
- **Sales Forecasting**: Accurate projections for daily sales across products.
- **Inventory Optimization**: Informed procurement planning to minimize stock shortages or overages.

