# Ex03-Univariate-Analysis
## Aim
To read the given data and perform the univariate analysis with different types of plots.

## Explanation
Univariate analysis is basically the simplest form to analyze data. Uni means one and this means that the data has only one kind of variable. The major reason for univariate analysis is to use the data to describe. The analysis will take data, summarise it, and then find some pattern in the data.

## Algorithm
### Step1
Read the given data.

### Step2
Get the information about the data.

### Step3
Remove the null values from the data.

### Step4
Mention the datatypes from the data.

### Step5
Count the values from the data.

### Step6
Do plots like boxplots,countplot,distribution plot,histogram plot.

## Program
Developed by : Mirudhula D

Registration Number : 212221230060
```
import pandas as pd
import numpy as np
import seaborn as sns
df=pd.read_csv("SuperStore.csv")
df
df.head()
df.info()
df.describe()
df.isnull().sum()
df.dtypes
df['Postal Code'].value_counts()
sns.boxplot(x="Postal Code", data=df)
sns.countplot(x="Postal Code", data=df)
sns.distplot(df["Postal Code"])
sns.histplot(x="Postal Code", data=df)
```
## Output
![OP1](https://user-images.githubusercontent.com/94828147/192077768-5217a417-0c12-43a9-b6e1-e0814b286c5a.png)

![op2](https://user-images.githubusercontent.com/94828147/192077794-d7042f2d-9d89-482a-a51e-3e3c1b955290.png)

![op3](https://user-images.githubusercontent.com/94828147/192077807-28095c57-32c0-47af-b024-113ea15687cd.png)

![op4](https://user-images.githubusercontent.com/94828147/192077823-d808e38c-2ba5-41fd-a85f-6f0461122dbd.png)

![op5](https://user-images.githubusercontent.com/94828147/192077912-7b57f726-6c06-4ae9-bdb7-03c70a900c1d.png)


![op6](https://user-images.githubusercontent.com/94828147/192077920-d0635ee0-e8c2-406b-b55c-fe8155b2e406.png)


![op7](https://user-images.githubusercontent.com/94828147/192077927-8491b31e-5098-4fbb-817f-86796a564183.png)


![op8](https://user-images.githubusercontent.com/94828147/192078036-64a9419f-8020-46e8-a611-2b7f22c6db27.png)

![op9](https://user-images.githubusercontent.com/94828147/192077953-c90eaa48-e47b-41b7-9364-5fbd9f2b242f.png)

![op10](https://user-images.githubusercontent.com/94828147/192077956-f04dad0e-3216-41d7-82a2-0b60e06f888a.png)

![op12](https://user-images.githubusercontent.com/94828147/192077960-14134dc2-42b2-4b1f-9573-7f69b009b3de.png)


## Result 
Thus we have read the given data and performed the univariate analysis with the different types of plot




