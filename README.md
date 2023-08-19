# Prediction of Product Sales
## Sales prediction for food items sold at various stores

**Author**: Shabana Patel 

### Business problem

The goal of this project is to help the retailer understand the properties of products and outlets that play an important roles in increasing sales.

### Data
[Original source](https:/https://datahack.analyticsvidhya.com/contest/practice-problem-big-mart-sales-iii/)
There are 8 523 rows and 12 columns in the dataset.

### Data dictionary

### Methods
To prepare this data, the data was cleaned, duplicate entries were removed and the following processes were performed:

## Exploratory Data Analysis
EDA is performed to understand the main characteristics, patterns and relationships within a datset. 

## Feature by feature inspection
Individual features in the dataset were considered to understand their distributions, patterns and significance in relation to the target variable. 

## Results

#### Outlet sales by outlet size


> Medium sized outlets seems to generate higher sales in comparison to other oulets of other sizes.

#### Outlet sales by outlet type

> Supermarket Type 3 outlet types seem to generate higher sales in comparison to other outlet types.

## Model

The final Machine Learning model chosen is a tuned Random Forest Regressor Model. Based on the testing dataset, the model can accurately explain 60% of the variability in the data, i.e. our models prediction matches the actual outcomes 60% of the time.

Using another measure, the Root Mean Squared Error (RMSE), we can say that on average the model's predictions differ from actual outcomes by $1 057 units.

## Limitations & Next Steps

If we consider the difference between the Mean Squared Error (MSE) on the training data ($895 161) and that of the test data ($1 116 665), it may indicate that the model is overfit.

Next steps could be exploring ways to get the model to generalize better, e.g. collecting more data, better feature selection, cross-validation, etc.

### For further information

For any additional questions, please contact **Shabana Patel**
