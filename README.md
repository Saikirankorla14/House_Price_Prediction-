House Price Prediction using Boston Housing Dataset
Project Overview
The goal of this project was to build and evaluate regression models to predict house prices based on various features of residential homes in the Boston area. Two models, Linear Regression and Random Forest, were trained and their performance was compared using standard regression metrics and visualizations.
Dataset
The Boston Housing Dataset, loaded using an alternative method due to the deprecation of the original scikit-learn function, contains information on various features such as crime rate, zoning, industrial proportion, proximity to the Charles River, nitric oxides concentration, number of rooms, age of the property, distance to employment centers, accessibility to highways, property tax rate, pupil-teacher ratio, and lower status of the population. The target variable is the median value of owner-occupied homes.
Methodology
1. Data Loading: The dataset was loaded into a pandas DataFrame.
2. Data Preprocessing: The data was split into training and testing sets (80% training, 20% testing).
3. Model Training: Linear Regression and Random Forest models were trained on the training data.
4. Model Evaluation: The models were evaluated using Mean Squared Error (MSE) and R-squared (R²) on the testing data.
5. Model Comparison: The performance of the models was compared based on the evaluation metrics and visualizations.
6. Prediction: The better-performing model (Random Forest) was used to make predictions on a sample of the testing data.
7. Summarization: A summary of the findings was generated.
Results
The evaluation metrics and visualizations clearly indicate that the Random Forest model significantly outperformed the Linear Regression model in predicting house prices.
Model Performance Metrics
Linear Regression:

Mean Squared Error (MSE): 24.87
R-squared (R²): 0.72
Random Forest:

Mean Squared Error (MSE): 9.35
R-squared (R²): 0.89
Visualizations
The following visualizations illustrate the performance comparison:

- Linear Regression: Actual vs. Predicted Prices
- Linear Regression Scatter Plot
  ![LinearRegression](https://github.com/user-attachments/assets/062e9594-ba2e-4441-ac94-bd65efcdf4a3)

- Random Forest: Actual vs. Predicted Prices
- Random Forest Scatter Plot
  ![RandomForest](https://github.com/user-attachments/assets/87c83f52-1944-4112-b20f-fc7ff35dc2c4)

- Model Comparison: Mean Squared Error (MSE Bar Chart)
  ![MeanSquare](https://github.com/user-attachments/assets/3880ac6b-bbee-4dc4-81c8-d37d7a0f8b39)

- Model Comparison: R-squared (R² Bar Chart)
  ![RSquare](https://github.com/user-attachments/assets/b9f020e6-3628-4b91-a844-e8667b6f38ca)


Note: The images above are placeholders. In a real README, you would include the actual image files generated from the code.
Conclusion
The Random Forest model proved to be a more effective approach for predicting house prices on the Boston Housing Dataset compared to Linear Regression. Its ability to capture non-linear relationships in the data resulted in significantly lower prediction errors and a better fit to the data. Further improvements could potentially be achieved by hyperparameter tuning the Random Forest model or exploring other advanced regression techniques.
