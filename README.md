#Overview:
This project focuses on predicting housing prices in Singapore using a dataset sourced from Kaggle. The prediction model considers various factors, including flat type, number of rooms, and lease commencement year, among others.

#Key Features:
**Feature Selection:** Utilized **ANOVA (Analysis of Variance)** to select the top eight features that significantly impact housing prices.
**Modeling:** Implemented several supervised regression techniques, including:
1. XGBoost
2. Linear Regression
3. Lasso Regression
4. Ridge Regression

#Feature Contribution Analysis:
- Applied **Shapley values** to assess the contribution of each feature to the model's predictions.
- Achieved an R-squared value of 0.79 with the best-performing model.

#Deployment:
- Deployed the model using FastAPI.
- Interacted with the API via Postman to validate predictions and performance.

#Summary:
The project effectively combines advanced feature selection, multiple regression techniques, and deployment strategies to deliver a robust housing price prediction model. The use of Shapley values enhances interpretability by providing insights into feature importance.

