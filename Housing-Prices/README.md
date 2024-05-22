# Housing Prices

## Project Overview
The Housing Prices project aims to predict the sales price of houses based on various features provided in the dataset. The goal is to build a regression model that accurately estimates the sale prices, which can help in understanding the key factors influencing property values.

## Goal
Predict the sales price for each house. For each Id in the test set, you must predict the value of the SalePrice variable.

## Metric
Submissions are evaluated on Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted value and the logarithm of the observed sales price. Taking logs means that errors in predicting expensive houses and cheap houses will affect the result equally.

## Dataset
### Source
[Housing Prices Kaggle Competition](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/overview)

### Dataset Description
The dataset contains information about house sales in Ames, Iowa, and includes various features that describe aspects of residential homes. These features cover:
- **Property Characteristics**: Information about the size, location, and type of the property.
- **House Features**: Details about the construction, style, and condition of the house.
- **Sale Information**: Data related to the sale type and condition.

## Exploratory Data Analysis (EDA)
Key insights from the data exploration include:
- Distributions of numerical and categorical variables.
- Relationships between features and the target variable, SalePrice.
- Identifying and handling missing values.

## Data Preprocessing
Steps taken to clean and prepare the data include:
- Handling missing values.
- Encoding categorical variables.
- Normalizing numerical features.

## Modeling
### Models Used
- Linear Regression
- Decision Trees
- Random Forest
- Gradient Boosting
- XGBoost

### Hyperparameters
Details of the hyperparameters used for each model and the tuning process.

## Evaluation
Metrics and methods used to evaluate model performance:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R-squared (R²)

## Results
Summary of the findings and performance of the models:
- Comparison of model performance using the evaluation metrics.
- Highlight the best-performing model.

## Conclusion
Final thoughts and potential improvements:
- Insights gained from the project.
- Recommendations for improving the model.
- Potential future work.
