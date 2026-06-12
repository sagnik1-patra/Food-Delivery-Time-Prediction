
# Food Delivery Time Prediction Report

## Objective

The objective of this project is to predict food delivery time using customer location, restaurant location, distance, weather, traffic, vehicle type, order priority, ratings, order cost, tip amount, and delivery partner experience.

## Dataset

Dataset Path:

C:\Users\NXTWAVE\Downloads\Food Delivery Time Prediction\Food_Delivery_Time_Prediction.csv

Rows: 200
Columns after processing: 24

## Preprocessing Steps

- Loaded the dataset.
- Checked and handled missing values.
- Extracted latitude and longitude from customer and restaurant locations.
- Calculated distance using the Haversine formula.
- Created Order_Hour and Rush_Hour features.
- Created Delivery_Status for logistic regression.
- Encoded categorical variables using one-hot encoding.
- Handled outliers using the IQR method.
- Dropped completely empty columns before imputation.
- Applied median imputation.
- Standardized features using StandardScaler.

## Linear Regression Results

MSE: 957.1594
RMSE: 30.9380
MAE: 26.5231
R2 Score: -0.0349

## Logistic Regression Results

Accuracy: 0.5000
Precision: 0.5000
Recall: 0.4500
F1 Score: 0.4737
ROC AUC: 0.4775

## Recommendations


Actionable Insights:

1. Optimize delivery routes using distance and traffic data.
2. Increase delivery staff during rush hours.
3. Adjust estimated delivery time during bad weather.
4. Assign high-priority orders to experienced delivery partners.
5. Use delay prediction to notify customers early.
6. Analyse vehicle type performance in different traffic conditions.
7. Improve delivery partner training to reduce delays.


## Saved Outputs

All outputs are saved inside:

C:\Users\NXTWAVE\Downloads\Food Delivery Time Prediction
