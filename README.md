<h1>Overview</h1>
This project aims to analyze an insurance dataset to uncover insights, hidden patterns, and trends related to financial and risk forecasting. Additionally, it seeks to identify the ideal customer profile for the insurance company.

## Objectives
- Analyze trends in claim amounts over time. Are claims increasing or decreasing? Are there any seasonal patterns?
- Determine which customer segments tend to file more claims or have higher claim amounts.
- Identify car dealerships or car models associated with higher claim amounts.
- Compare the amount paid for insurance premiums with the claim amounts to assess the profitability of different customer segments.
- Identify patterns that may indicate fraudulent claims.
- Determine which income levels are associated with lower claim amounts or fewer claims.
- Analyze differences in claim behavior between genders.
- Identify cities or dealers with customers having lower risk profiles.

### Libraries Used
- [Pandas](https://pandas.pydata.org/docs/getting_started/install.html#installing-from-pypi)
- [Numpy](https://numpy.org/install/)
- [Seaborn](https://seaborn.pydata.org/installing.html)
- [Scikit-learn](https://scikit-learn.org/stable/install.html)
- [Statsmodel](https://www.statsmodels.org/stable/install.html)

```
import pandas as pd
import numpy as np
import seaborn as sns
import statsmodels.api as sm
```
#### Techniques and Models
- [Label Encoder](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.LabelEncoder.html)
- [OneHot Encoder](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.OneHotEncoder.html)
- [Random Forest Regressor](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html)
- [Random Forest Classifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html)
- [Linear Regression](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html)
- [Isolation Forest](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.IsolationForest.html)
- [Mean Absolute Error](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.mean_absolute_error.html)

```
from sklearn.preprocessing import LabelEncoder
from sklearn.preprocessing import OneHotEncoder
from sklearn.ensemble import RandomForestRegressor
from sklearn.ensemble import RandomForestClassifier
from sklearn.linear_model import LinearRegression
from sklearn.ensemble import IsolationForest
from sklearn.metrics import mean_absolute_error, mean_squared_error
```



