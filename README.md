# Ex.No: 01A PLOT A TIME SERIES DATA
###  Date: 20.04.2026

# AIM:
To Develop a python program to Plot a time series data (population/ market price of a commodity temperature.


# ALGORITHM:
1. Import the required packages like pandas and matplot
2. Read the dataset using the pandas
3. Calculate the mean for the respective column.
4. Plot the data according to need and can be altered monthly, or yearly.
5. Display the graph.


# PROGRAM:

```
from matplotlib import pyplot as plt
import pandas as pd
import seaborn as sns

df=pd.read_csv("customer.csv")
df.head()

plt.figure(figsize=(12,6))
plt.title("Salary Increase Chart ")
plt.title('Salary Prediction')
plt.xlabel('Salary')
plt.ylabel('Employee ID')
sns.lineplot(x=df.id,y=df.Income)
```



# OUTPUT:

<img width="1005" height="545" alt="download" src="https://github.com/user-attachments/assets/2059c887-2f4c-4a6e-bfaa-a5ef73d2160b" />




# RESULT:
Thus we have created the python code for plotting the time series of given data.
