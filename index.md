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


You can use the [editor on GitHub](https://github.com/zhongchurong/K6312-group10/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Dataset
## Code

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/zhongchurong/K6312-group10/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
