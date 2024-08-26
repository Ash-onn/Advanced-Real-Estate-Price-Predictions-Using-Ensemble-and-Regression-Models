# Advanced-Real-Estate-Price-Predictions-Using-Ensemble-and-Regression-Models
Overview
This project implements an advanced real estate price prediction model utilizing multiple regression techniques. The model is designed to predict property prices based on various features, with a focus on enhancing accuracy through hyperparameter tuning and rigorous evaluation methods. Key regression techniques used include Linear Regression, Decision Tree Regressor, Random Forest Regressor, and Gradient Boosting Regressor.

Features
Data Cleaning: The dataset was meticulously cleaned, removing outliers and handling missing values to ensure high-quality input for model training.
Feature Engineering: Key features were engineered, including polynomial features and categorical encoding, to enhance model accuracy.
Model Training: Trained eight different regression models, including:
Linear Regression: A simple yet powerful baseline model.
Decision Tree Regressor: A non-linear model capable of capturing complex interactions between features.
Random Forest Regressor: An ensemble model that improves accuracy by combining multiple decision trees.
Gradient Boosting Regressor: A powerful ensemble model that iteratively improves predictions by focusing on errors in previous iterations.
Hyperparameter Tuning: Leveraged Optuna to fine-tune the Gradient Boosting Regressor, optimizing parameters like max_depth and learning_rate to achieve the best model performance.
Cross-Validation: Applied 5-fold cross-validation to ensure the model’s robustness and generalizability.
Key Metrics
Best Model: Gradient Boosting Regressor
Initial Performance:
MSE: 11.296
R²: 0.887
After Hyperparameter Tuning:
MSE: 10.1956
R²: 0.894
Cross-Validation Results:
Mean MSE: 15.589
MSE Standard Deviation: 9.529
Test Set Performance:
MSE: 10.539
R²: 0.894
RMSE: 3.246 (Improved from baseline RMSE of 9.997)

Results
The final model significantly improved prediction accuracy, with a 9.7% reduction in MSE and a RMSE improvement from 9.997 to 3.246. The optimized Gradient Boosting Regressor demonstrates the effectiveness of advanced machine learning techniques in real-world applications, offering robust and reliable price predictions.

Conclusion
This project showcases the power of advanced regression techniques and hyperparameter tuning in building a high-performance real estate price prediction model. The model's strong predictive capabilities make it a valuable tool for real estate analysis and investment decision-making.

Future Work
Feature Expansion: Explore additional features such as economic indicators or geographic data to further enhance model accuracy.
Model Comparison: Experiment with other advanced models like XGBoost or LightGBM for potential performance gains.
Deployment: Implement a web-based interface for real-time price predictions.

Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

License
This project is licensed under the MIT License - see the LICENSE file for details.
