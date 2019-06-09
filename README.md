## Welcome to Machine Learning Housing Corporation!
In this project, I will build a model to predict the house price using [the Kaggle dataset](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/overview). This data has 79 explanatory variables describing every aspect of residential homes in Ames, Iowa. My model will learn from this data and be able to predict thefinal price of each home. 
### Frame the Problem
First, I need to frame the problem:
* It is clearly a typical supervised learning task since labeled training examples are given.
* It is also a typical regression task since prediction of a value is asked.
* This is a multiple regression problem since the model will use multiple features to make a prediction.
* It is also a univariate regression problem since we are only trying to predict a single value for each house.
* There is no continuous data flow, no particular need to adjust to changing data rapidly, and the data is small enough to fit in memory, so plain batch learning should do just fine.
