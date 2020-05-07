# Information Mining in IMDb Movie Dataset
#### Welcome to group 10

#### Group member: 
##### Cai Jingyi
##### Zhong Churong
##### Chen Yidian
##### Yu Zeyuan

## Dataset
You can download the [dataset](https://github.com/zhongchurong/K6312-group10/tree/master/Dataset)
## Code
### Behavior Analysis & Data Visulization
#### Releasing Data Analysis
```markdown
import os
import numpy as np
import matplotlib.pyplot as plt
import pandas as pd
import seaborn as sns
data = pd.read_csv("movie.csv", sep=",")
date = data[['date_published']].values
print(date[0][0])
print(len(date))
daylist = []
for i in range(len(date)):
    day = date[i][0]
    day = day.split('/')
    day = int(day[-1])
    #print(day)
    daylist.append(day)
yearlist = []
for i in range(len(date)):
    year = date[i][0]
    year = year.split('/')
    year = int(year[0])
    yearlist.append(year)
sns.countplot(yearlist)
plt.xlabel('year_punished')
plt.xticks(fontsize=10, color="black", rotation=90)
sns.countplot(daylist)
plt.xlabel('date_punished')
plt.subplot
sns.countplot(data['week'])
plt.subplot
sns.countplot(data['month_published'])
comedy = data['Comedy']
drama = data['Drama']
```
