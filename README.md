# Premier-League-Table-Prediction

## README:

Contributors: 
#### Tejeswara Nehru (U2220197K)
#### Michael Santoso (U2221525L)
#### Nguyen Tien Dat (John) (U2220949L)


### About:
Contained within are the source codes for our SC1015 (Introduction to Data Science and Artificial Intelligence) Mini-Project. Our mini-project aims to investigate the factors which contribute to a team’s performance in terms of winning and losing games and use ML models to predict future matches based on past matches. Our personal objective from this project is to predict the top 6 teams going into the Champions League (for top 4 teams) and Europa league (5th and 6th teams)

Models Used: Linear Regression, Neural Network, and Random Forest Regression.

### Conclusion: 
Exploring our additional learning objectives, we learnt that home advantage plays a big factor in match performance, with some teams going as high as 38% more likely to win on their home field. In addition, goal difference (GD) has a positive correlation to the team’s performance, meaning that a higher GD will lead to a better performance of the team. Lastly, we found that there is a positive linear relationship between a team’s form (status of previous 5 matches) and their likelihood of winning a match, in which a team having a better form than the opponent would have higher likelihood in winning the match.

We found that there are 6 reliable variables that could be used for the ML models, i.e., HTFormPts, ATFormPts, HTGD, ATGD, DiffPts, and DiffFormPts. Using these variables, we use the 3 ML models to predict the 2017-2018 EPL ranking, then comparing it with the actual ranking Through comparing it using the MSE and RMSE values, we can see that the neural network works best in predicting data, followed by the random forest, and lastly the linear regression. To complete our personal objectives, we found that in the top 6 teams, 5 teams are consistently there throughout all the ML models, namely Man City, Man United, Tottenham, Liverpool, and Chelsea, hence, we can be certain that these teams would likely qualify for the Champions/Europa League. Furthermore, we can extend our project to predict future seasons rankings to a large accuracy. 

### What did we learn from this project?
In this project, we explored the use of linear regression, neural networks, and random forest algorithms to predict football team tables. We found that the neural network model performed the best, followed by the random forest and linear regression models.
The superior performance of the neural network and random forest models in predicting the football team table can be attributed to their ability to handle the complexity of the high-dimensional dataset with complex interactions between features. The neural network's capability to capture complex patterns and relationships in the data and the random forest's effectiveness in handling high-dimensional datasets with complex interactions between features likely contributed to their better performance. On the other hand, the linear regression model's inability to capture complex nonlinear relationships in the data may have led to its inferior performance compared to the other models. Overall, the complexity of the dataset played a significant role in the performance differences between the models.
Through this project, we learned the importance of selecting the right algorithm for a particular task, as well as the significance of hyperparameter tuning to achieve optimal results. We also learned that neural networks, with their ability to capture complex patterns in data, can be highly effective in predicting outcomes for sports-related datasets, since sports datasets often contain a large number of variables and interactions between those variables, making traditional statistical methods difficult to use.
Moreover, we learned the importance of carefully selecting and preprocessing the dataset to ensure accurate predictions. In this project, we used a dataset spanning from 2000-2017, and this provided valuable insights into how football teams have performed over the years. We also learned the importance of feature selection, as not all features may be relevant in making accurate predictions. 
Overall, this project provided us with a deeper understanding of how machine learning algorithms can be applied to predict football team tables, as well as the importance of data preprocessing and feature selection in achieving accurate results. However, there are some possible area of improvements, as stated below:

#### Data Handling for Relegated Teams
The dataset may be skewed towards the more established and consistent Premier League teams, such as Manchester United and Manchester City, as they have been part of the league for a longer time and therefore have more available data.
On the other hand, the relegated teams that have only participated in a few seasons in the Premier League may have limited data available, which could potentially affect the overall accuracy of the models. To address this issue, we need to use transfer learning techniques to leverage knowledge from related tasks or domains. For instance, one could pretrain a model on a large dataset of football matches from different leagues and then fine-tune it on the Premier League dataset. This could potentially improve the model's ability to handle limited data for the relegated teams while still maintaining the accuracy on the overall prediction task.

#### Incorporating Additional Features
We only used a subset of available features from our dataset to train our models. It would be worthwhile to explore other features, such as team budgets, transfer data, or injury data, which could provide additional insights into team performance and potentially improve the accuracy of our predictions.

#### Implementing Time-Series Analysis
Football team performance can be influenced by a variety of factors such as injuries, transfers, and managerial changes. Implementing time-series analysis techniques could help capture the temporal dependencies and patterns in team performance over time. This could lead to more accurate and reliable predictions of future team performance.

#### Incorporating External Data Sources
In addition to using the existing dataset, we could consider incorporating external data sources such as weather data, social media sentiment, or news articles. These data sources could provide additional context and insights into team performance and improve the accuracy of our predictions.


### References:

Kaggle. (n.d.). English Premier League. Retrieved April 22, 2023, from https://www.kaggle.com/datasets/saife245/english-premier-league

Jeong, W. (2021). EPL Winner. Retrieved April 22, 2023, from https://www.kaggle.com/code/jeongwonwoobit/epl-winner

GeeksforGeeks. (2021, February 24). Random Forest Regression in Python. Retrieved April 22, 2023, from https://www.geeksforgeeks.org/random-forest-regression-in-python/
