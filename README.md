# Data Analysis and fitting a Linear Regression Model on a football dataset using Python  
  
**Static Jupyter Notebook** : [link](https://github.com/pillaikartik10/python-football-data-analysis/blob/main/football.ipynb)  
**Interactive Binder** : [link](https://mybinder.org/v2/gh/pillaikartik10/python-football-data-analysis/709de146bda7b950cef9546139ee8d982fe8e086)  
  
In this project, we are going to perform some simple Data Analysis with the footballing dataset in hand, and implement a Linear Regression Model using scikit-learn.  
  
## Requirements and Dependencies  
  
**Dataset** : [Kaggle link](https://www.kaggle.com/martj42/international-football-results-from-1872-to-2017)  [Github link](https://github.com/pillaikartik10/python-football-data-analysis/blob/main/results.csv)  
  
The dataset contains records of 42,000 + international football games. The available information includes the participant teams, goals scored by each team, date, venue etc.  
  
**Dependencies:**  
numpy        : 1.20.2  
plotly       : 4.14.3  
matplotlib   : 3.4.2  
pandas       : 1.2.3  
chart_studio : 1.1.0  
scipy        : 1.6.3
scikit-learn : 0.24.2
sklearn      : 0.0
threadpoolctl: 2.1.0
joblib       : 1.0.1

**NOTE** : If you are using the Binder link, it will automatically recreate the environment and download these dependencies.  
  
## The Project  
  
On the basis of the available data, we try to find out the following :  
  
1. In which Tournament was the highest number of games played?  
2. Which are the top 10 teams with the most wins?  
3. Which are the best teams with respect to Winning percentage (having played a minimum of 100 games)?  
4. Calculating Total Goals scored, and find out the top teams w.r.t. Goals scored per game.  
5. Check for any correlation between the Winning %, and Goals per game.  
  
Finally, we fit a Simple Linear Regression Model on the Winning % and Goals scored per game, and find out the accuracy of the prediction by the machine model.
