# FIFA Women's World Cup Prediction with ML😎

## Little summary
Hi, this is my first public project on GitHub.  In a nutshell, I'm building as the final project of my AllWomen bootcamp, a (supervised) machine learning model to predict the results of the 2023 women's world cup football tournament. 

## Status of the project
The status of the project is finalized! Here you will find a figure with the predicted results for the world cup! 
 
## Dataset and libraries used
This model was made on a jupyter notebook, and I used the following libraries: Numpy, Pandas, Seaborn, Plt, Sklearn. This last one is specifically used to create the model itself, that is to say to perform the Logistic Regression. 
To perform the above, I rely on the dataset provided in Kagle by Mart Jürisoo, [link](https://www.kaggle.com/datasets/martj42/womens-international-football-results).

## Steps
1. Collect and clean the data: Gather historical data on past Women's World Cup matches, including statistics such as scores and teams.

2. Exploratory data analysis: Visualization techniques to explore data and identify patterns and trends. Here I saw that the USA is historically the better team, there is a higher ratio of home goals to away goals, the number of women's teams has increased and the number of games per year (except in pandemic) has increased.

3. Feature selection: Select the most relevant variables from the data set to use in the predictive model. In this case, the goals scored by the 'home' team and the 'away' team were used. 

4. Model selection: Select a suitable machine learning algorithm for the problem, such as logistic regression, which is used to predict a binary outcome.

5. Model training: Train the selected model on the selected data. This involves specifying the model parameters and fitting the model to the training data.

6. Model evaluation: Evaluate the performance of the model using performance metrics such as accuracy, precision, and recall. After hyperparameter tuning, an accuracy of 74.7% was achieved.
