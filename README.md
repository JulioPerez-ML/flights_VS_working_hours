# Motivation
This is just a entertaining try to use some data from my company and to build a regression model to try to predict the productivity.

# Flights vs working hours 

In this project you will find a extense analysis of a dataset that includes some data cleansing and data wrangling. Then we continue with some charts and we buildsome models.
First trying withe statsmodel package and finally with sklearn package. After that, we analyse the variability of the data using time series forecasting (Sarimax used in this case).
The time series analysis was guided by Susan Li article, which is in References

## Files in this repository
- Csv file
- Python notebook with all the chunks of code

## Installation and packages
You just need to copy the following lines to import the package and you will be able to reproduce all the content:
``` 
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import statsmodels.api as sm
import itertools
sns.set()
```

## Results
The results are shown in the differents charts of the notebook. The models seems to be working nicely but we can improve their performance for sure.

## Issues
Nothing to comment here. All is working properly

## References

> [StackOverflow](https://stackoverflow.com/)

> [Towards Data Science - Susan Li Article](https://towardsdatascience.com/an-end-to-end-project-on-time-series-analysis-and-forecasting-with-python-4835e6bf050b)

## License
Feel free to use the code here as you would like!
