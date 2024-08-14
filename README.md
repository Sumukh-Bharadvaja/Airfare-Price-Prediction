# Dynamic Pricing of Flight Tickets Analysis

## Project Overview
This project focuses on the dynamic pricing strategies employed by commercial airlines such as Qatar Airways, Etihad, and AirAsia. Utilizing big data technologies, we aim to understand and predict fare changes influenced by market demand and historical pricing data. The project utilizes Decision Trees and Random Forest algorithms to identify key factors affecting price variations and to validate the accuracy of our predictive models.

[View Notebook!](./Team_7_AirFare_Price_Feature_Predicition.html/)

## Objectives
- **Data Analysis**: Employ advanced data analytics techniques on datasets comprising over 400,000 records.
- **Model Development**: Use machine learning models like Decision Trees, Random Forest, Gradient Boosting, and XGBoost to predict flight prices.
- **Feature Importance**: Explore which features most significantly impact flight prices using model insights.
- **Performance Evaluation**: Assess model performance using metrics such as RMSE, MAE, and R².

## Data
Data was sourced from EaseMyTrip and includes 400k+ records for flights across India, featuring attributes like:
- Date of Journey, Journey Day, Airline, Flight Code
- Class, Source, Departure, Total Stops, Arrival, Destination
- Duration in Hours, Days Left, and Fare

## Methodology
1. **Data Preprocessing**: Data cleaning, normalization, and type conversion for model readiness.
2. **Exploratory Data Analysis (EDA)**: Insights into pricing patterns and feature distributions.
3. **Regression Modeling**: Implementing various machine learning algorithms to predict flight prices.
4. **Model Validation**: Using evaluation metrics to refine and validate the predictive models.

## Model Comparison
| Model Type        | R² Score | RMSE  | Observations                      |
|-------------------|----------|-------|-----------------------------------|
| Linear Regression | 20%      | 15000 | Poor performance; high variance.  |
| Decision Tree     | 87%      | 7068  | Good fit but potential overfitting|
| Random Forest     | 87%      | 7068  | Reduces overfitting; robust.      |
| Gradient Boosting | 89%      | 6500  | Better than Random Forest.        |
| XGBoost           | 91%      | -     | Best model; optimal for dataset.  |

## Key Findings
- XGBoost provided the best performance, capturing approximately 91% of data variability.
- Ensemble methods and boosting algorithms demonstrated high effectiveness in predicting dynamic flight pricing.
- Decision Trees and Random Forest showed robust performance but had concerns about overfitting, which were mitigated using ensemble techniques.

## Future Work
- **Feature Expansion**: Integrating real-time market trends and customer behavior metrics to enhance model accuracy.
- **Reinforcement Learning**: Implementing models that adapt dynamically to changing market conditions.

## References
1. Schosser, M. (2019). "Towards a maturity model for big data analytics in airline network planning."
2. Zhao, Z., You, J., Gan, G., Li, X., & Ding, J. (2021). "Civil airline fare prediction with a multi-attribute dual-stage attention mechanism."

Thank you for your interest in our project on dynamic pricing analysis for flight tickets.
