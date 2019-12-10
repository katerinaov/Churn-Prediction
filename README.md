# Churn-Prediction

# The Churn prediction for telecom data

If it's not possible to open the notebook in GitHub, please open this [link](https://nbviewer.jupyter.org/github/katerinaov/Churn-Prediction/blob/master/Liberty%20Global-Case%20Syudy.ipynb)

The notebook contains:
- Data exploration of the dataset
- Data cleaning
- Feature Engineering
- Data Modeling
- Model evaluation
- Hyper-parameters tuning

# Observations on the dataset
1. The dataset has 7043 observations with a target variable 'Churn', which have not balanced distribution.(only 25% of the observations are for churned customers.
2. There's a majority of categorical variables and only 3 numeric.
3. The variables almost do not have a collinearity

# Metrics to observe

As the dataset is very imbalanced, and we're more interested in minimising the incorrect predictions of not churned, when actually churned customers (False Negatives).

That's why our target metrics should be:
- Recall
- Precision-Recall curve

# Results of the project
For this dataset, there are 2 models performed well with a recall approx of 80%:
- Logistic Regression
- GuassianNB

# Further improvement
- Add demographics features ( as place where customer lives, age)
- Customer satisfaction features : customer support calls, number of problems reported)
- More data, especially for churned customers
- With bigger dataset, try ensemble models for better performance



























