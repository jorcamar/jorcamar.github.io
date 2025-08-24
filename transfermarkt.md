[🔙 Back to the portfolio](https://jorcamar.github.io/#data-engineering-with-a-complex-database)

# Data Engineering with a Complex Database

> ‼️ This is just a summary for the project. **For reading the full steps, code and explanation, please [go to the Jupyter Notebook 📙.](notebooks/lr-transfermarkt.html)**


## 📖 Project Description

Big Data has been revolutionary for football clubs all around the world this last decade. For example, a team of scientists specialized in data have been, in part, responsibles of the great recruitment moves from Liverpool FC that have led them to win the Premier League after 30 long years. It can guide in which player to sign, what are the most important problems in the club, performance analysis, fitness optimization...

In this project, two prediction tasks were performed: predicting market value of players, and predict if a team is going to classify for some european competition. For this, two datasets with different sources were used. 

The first model was a Linear Regression model for predicting the market value of a player after a season considering as predictors his stats, like goals or assists. The second model was a Generalized Linear Model for predicting whether a football team is going to classify to Champions League (UCL), Europa League (UEL) or Conference League (UECL). 

The two types of models used (linear regression and GLM) are simple but very effective for getting insights into the data, which is the main objective in these types of task. However, it is also shown in the project how GLMs can model non-linear and complex relationships while maintaining this interpretability, making them an effective and flexible option which is often overlooked in ML problems.


---

## 📙 Notebook

In the [notebook](notebooks/lr-transfermarkt.html), every step of the work for both problems is detailed: the scraping of the data from Transfermarkt, the EDA, the feature engineering, the development of the models and the final results and conclusions.