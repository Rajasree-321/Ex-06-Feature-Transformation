# Ex-06-Feature-Transformation
# AIM
 To read the given data and perform Feature Transformation process and save the data to a file.
# EXPLANATION
 Feature Transformation is a technique by which we can boost our model performance.Feature transformation is a mathematical transformation in which we apply a mathematical formula to a particular column(feature) and transform the values which are useful for our further analysis.
# ALGORITHM
STEP 1
Read the given Data

STEP 2
Clean the Data Set using Data Cleaning Process

STEP 3
Apply Feature Transformation techniques to all the features of the data set

STEP 4
Save the data to the file

# CODE 

import numpy as np

import pandas as pd

import matplotlib.pyplot as plt

import statsmodels.api as sm

import scipy.stats as statsdf = pd.read_csv("/content/Data_to_Transform.csv")

print(df)

![image](https://github.com/Rajasree-321/Ex-06-Feature-Transformation/assets/96918911/11b170b4-e293-482a-af1c-16c4bf77450f)

df.head()

![image](https://github.com/Rajasree-321/Ex-06-Feature-Transformation/assets/96918911/3b48d981-185d-4f59-b95f-90f7bab716bb)

df.info()

df.describe()

![image](https://github.com/Rajasree-321/Ex-06-Feature-Transformation/assets/96918911/e0298e39-0f28-45fe-b6c9-88e8af9c7011)

# OUTPUT

![image](https://github.com/Rajasree-321/Ex-06-Feature-Transformation/assets/96918911/0f516ab8-a039-4e1a-934d-b0e1636530d0)

![image](https://github.com/Rajasree-321/Ex-06-Feature-Transformation/assets/96918911/7d4fd4ce-41c7-423f-8dd5-846414bb0893)

![image](https://github.com/Rajasree-321/Ex-06-Feature-Transformation/assets/96918911/9bbb080b-34f5-4371-8957-964a4bc9cb6d)

![image](https://github.com/Rajasree-321/Ex-06-Feature-Transformation/assets/96918911/a0846093-34f1-44dc-a3a1-34e6dd74a113)

![image](https://github.com/Rajasree-321/Ex-06-Feature-Transformation/assets/96918911/d07f01f6-4011-4c1e-ba0f-e09757522c10)

![image](https://github.com/Rajasree-321/Ex-06-Feature-Transformation/assets/96918911/3c2c15b7-4d75-47d4-9298-1bd59e247fd4)

![image](https://github.com/Rajasree-321/Ex-06-Feature-Transformation/assets/96918911/8e42f02f-9879-4f1d-a738-bbd9c5eed187)

![image](https://github.com/Rajasree-321/Ex-06-Feature-Transformation/assets/96918911/c356356a-f8c7-4bf6-b9b1-e581eca189ce)

![image](https://github.com/Rajasree-321/Ex-06-Feature-Transformation/assets/96918911/b2f06e3b-2f45-410d-9d53-f467903fb656)

![image](https://github.com/Rajasree-321/Ex-06-Feature-Transformation/assets/96918911/3e52611e-27a3-4394-a41a-3ecc037abd33)

# RESULT
Thus the Feature Transformation for the given datasets had been executed successfully.


