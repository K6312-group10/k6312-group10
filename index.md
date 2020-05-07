# Information Mining in IMDb Movie Dataset
##### Welcome to group 10~~~~
![截屏2020-05-07 下午9.24.32.png](https://i.loli.net/2020/05/07/fyDtFha4ukdOcXe.png)
### Group member: 
### Cai Jingyi/ Zhong Churong/ Chen Yidian/ Yu Zeyuan

## 1. Dataset
You can download the [dataset](https://github.com/zhongchurong/K6312-group10/tree/master/Dataset) here.
## 2. Behavior Analysis & Data Visulization
###### In this part, we conducted behavior analysis on the IMDb movie data to see if there is any interesting phenomenon in the movie industry. The two topics we focused on are movie genre and releasing date related phenomenon. The final result will be visualized through graphs, where insights can be gained. 
##### You can download the [code](https://github.com/K6312-group10/k6312-group10/blob/master/Code/Visualization.ipynb) here.
## 3. Multi-regression
###### Multiple linear regression tries to interpret possible linear relationships between certain input and output variables. It is concerned with studying to what extent the behavior of a single output variable Y is inﬂuenced by a set of input variables X. Based on our data collection, we take these two features as the dependent variables: avg_vote (movie rating) and votes (numbers of movie rating), because they are vital features related to the success of movie. In addition, we also calculate the influence of different genres on getting higher rating/voting. The results would be visualized through graphs, where insights can be gained.
##### You can download the [code](https://github.com/K6312-group10/k6312-group10/blob/master/Code/Multi_reg.ipynb) here.
## 4. Classification
###### Movie websites like Rotten Tomatoes or IMDb are expected to have a prior prediction or analysis before the release of a new movie and accordingly provide “recommendation index” to the website viewers based on the movie information including release date, genre, cast, directors, etc. In such scenarios, the accurate predicted rating may not be required, but instead, a class property of whether it will be a good or bad movie together with the probability may display a greater value. Therefore, classification models are considered to achieve such goals based on the collected training samples.
##### You can download the code for [logistic regression](https://github.com/K6312-group10/k6312-group10/blob/master/Code/Logistic_Regression.ipynbb) here.
##### You can download the code for [KNN_classification](https://github.com/K6312-group10/k6312-group10/blob/master/Code/KNN_Classification.ipynb) here.
