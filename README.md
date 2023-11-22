#  Bike Sharing Case Study

Multiple Linear Regression

 Bike Sharing Case Study
 
 Problem Statement
        A US bike-sharing provider BoomBikes has recently suffered considerable dips in
    their revenues due to the ongoing Corona 
    pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come
    up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end,
    and the economy restores to a healthy state. 

 The company wants to know:

      - Which variables are significant in predicting the demand for shared bikes.
      - How well those variables describe the bike demands







## Conclusions
Final Result:
Train Set R2 = 0.7635053374997316
Train Ser Adjust R2 = 0.7492171183070071
Test Set R2 = 0.7479212951462257
Test Ser Adjust R2 = 0.733308036893833

The perfect fit line is 

cnt = 0.2385(yr) + 0.0076(weekday) + 0.6161(atemp) - 0.0552(Mist)



<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sn
import sklearn
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import MinMaxScaler
import statsmodels.api as sm
from statsmodels.stats.outliers_influence import variance_inflation_factor
from sklearn.metrics import r2_score
from sklearn.feature_selection import RFE
from sklearn.linear_model import LinearRegression
import warnings




## Contact
Created by [niviinfotechs@gmail.com] - feel free to contact me!


