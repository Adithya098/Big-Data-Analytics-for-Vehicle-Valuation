# Vehicle Resale Price Prediction Using Machine Learning

## Motivation
Determining a vehicle's true resale value is a complex challenge in today's automobile market. Traditional methods rely on intuition and limited information, leading to inconsistent pricing. This project leverages a data-driven approach, utilizing machine learning to analyze millions of car listings and predict vehicle prices more accurately.

This dataset contains over 3 million new and used vehicle listings from across the United States. The dataset can be accessed through Kaggle at [USA-used-cars-dataset](https://www.kaggle.com/datasets/ananaymital/us-used-cars-dataset).

For more detailed information on the project, including in-depth explanations about the approaches, experimentation, results, and lessons learned, please refer to the `project presentation` (Vehicle_Valuation_Final_Report.pdf) and `project report`(Project_Presentation_Vehicle_Valuation.pdf), attached in this repository.

My best model, leveraging **XGBoost with Bagging and advanced Feature Engineering**, achieved a **Mean Absolute Percentage Error (MAPE) of 4%**, making it highly accurate for predicting vehicle prices. This low **MAPE of 4%** reflects the model's ability to produce predictions with minimal deviation from actual values, ensuring reliability for real-world applications.


---

## Target Task
The goal of this project is to predict the resale price of vehicles by analyzing features such as mileage, age, brand, color, engine specifications, and other attributes. The project employs regression-based machine learning models to identify key determinants of resale value and deliver precise predictions.

### Regression Models Used:
1. Linear Regression
2. Decision Trees
3. Random Forest
4. Gradient Boosted Trees (GBT)
5. Extreme Gradient Boosting (XGBoost)

### Why These Models?
- **Linear Regression** captures simple relationships between features and price.
- **Decision Trees** and **Random Forests** handle complex interactions and non-linearities.
- **Boosting Methods (GBT and XGBoost)** iteratively refine predictions, improving accuracy and robustness.
This diverse selection ensures comprehensive modeling of vehicle prices.

---

## Key Performance Indicators (KPIs)
To evaluate the performance of the regression models, the following metrics were used:

1. **R² Score:** Measures how well the model explains the variance in the target variable, reflecting model fit.
2. **MAE (Mean Absolute Error):** Indicates the average magnitude of errors in predictions, irrespective of direction.
3. **MAPE (Mean Absolute Percentage Error):** Shows the average percentage difference between predicted and actual values, reflecting relative prediction accuracy.
4. **RMSE (Root Mean Square Error):** Quantifies prediction errors while penalizing larger errors more heavily, offering a sensitive performance measure.

*Note:* Both MAE and RMSE are expressed in dollars to directly represent their impact on price predictions.

---

## Project Workflow
![image](https://github.com/user-attachments/assets/b040f1e6-c7a4-4610-96f3-68aa286fb2da)


