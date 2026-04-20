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
df=pd.read_csv("sales.csv")
df.head()
plt.title('Sales prediction')
plt.xlabel('Sales')
plt.ylabel('Density')
sns.kdeplot(df['Sales'])
plt.grid()
plt.show()
```



# OUTPUT:

<img width="576" height="453" alt="download" src="https://github.com/user-attachments/assets/149dc1d7-283f-47ab-8223-422b22e5ae13" />



# RESULT:
Thus we have created the python code for plotting the time series of given data.
