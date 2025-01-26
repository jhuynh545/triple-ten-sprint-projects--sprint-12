# triple-ten-sprint-projects--sprint-12

Rusty Bargain, a used car sales service, is developing an app to estimate the market value of cars. Your task is to build a machine learning model that accurately predicts car values based on historical data, including technical specifications, trim versions, and prices. The project emphasizes not only prediction accuracy but also computational efficiency.

Key Objectives:

Prediction Quality: Use the RMSE metric to evaluate model performance.
Prediction Speed: Ensure the model provides quick predictions for real-time app usage.

Training Time: Optimize training duration for efficient model development.
Methodology:

Baseline Check: Use linear regression as a benchmark for sanity checks. If gradient boosting underperforms compared to linear regression, re-evaluate your methodology.

Gradient Boosting:
Work with LightGBM to develop gradient boosting models. Experiment with multiple hyperparameter configurations.
Optionally, incorporate CatBoost and XGBoost for comparative analysis.

Tree-Based Models: Include a tree-based algorithm (e.g., random forest) with hyperparameter tuning to enhance prediction quality.

Categorical Features: Handle categorical variables appropriately:
Use built-in encoding for LightGBM and CatBoost.
Apply one-hot encoding (OHE) for XGBoost.

Outcome: 
Deliver a high-performing, efficient model capable of producing accurate car value predictions while balancing training and prediction speed.
