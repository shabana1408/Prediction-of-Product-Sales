![prediction_of_product_sales](https://github.com/shabana1408/Prediction-of-Product-Sales/assets/138613948/4ad2d3f3-ff2b-4900-a19a-73b4e9b20201)

# Prediction of Product Sales
## Sales prediction for food items sold at various stores

**Author**: Shabana Patel 

### Business problem

The goal of this project is to help the retailer understand the properties of products and outlets that play an important roles in increasing sales.

### Data dictionary
[Original source](https:/https://datahack.analyticsvidhya.com/contest/practice-problem-big-mart-sales-iii/)

There are 8 523 rows and 12 columns in the dataset.

<img width="383" alt="dd_sales_predictions" src="https://github.com/shabana1408/Prediction-of-Product-Sales/assets/138613948/be96d30d-b6cf-4b35-a5b7-14cf42716e8c">

### Methods
To prepare the data, the data was cleaned, duplicate entries were removed and the following processes were performed:

## Exploratory Data Analysis
EDA is performed to understand the main characteristics, patterns and relationships within a datset. 

## Feature by feature inspection
Individual features in the dataset were considered to understand their distributions, patterns and significance in relation to the target variable. 

## Results

#### Outlet sales by outlet size
![viz1_outlet_size](https://github.com/shabana1408/Prediction-of-Product-Sales/assets/138613948/3fa2b27f-39a3-4c4f-8416-ffa3066b72fd)

> Medium sized outlets seemed to generate higher sales in comparison to oulets of other sizes.

#### Outlet sales by outlet type
![viz1_outlet_type](https://github.com/shabana1408/Prediction-of-Product-Sales/assets/138613948/992d7863-8f55-433b-b551-68ae9e66cec4)

> Supermarket Type 3 outlet types seem to generate higher sales in comparison to other outlet types.

## Model

The final Machine Learning model chosen is a tuned Random Forest Regressor Model. Based on the testing dataset, the model can accurately explain 60% of the variability in the data, i.e. our models prediction matches the actual outcomes 60% of the time.

Using another measure, the Root Mean Squared Error (RMSE), we can say that on average the model's predictions differ from actual outcomes by $1 057.

## Limitations & Next Steps

If we consider the difference between the Mean Squared Error (MSE) on the training data ($895 161) and that of the test data ($1 116 665), it may indicate that the model is overfit.

Next steps could be exploring ways to get the model to generalize better, e.g. collecting more data, better feature selection, cross-validation, etc.
