# Baseball Play WAR Model

In this project, we'll predict future season stats for baseball players. Specifically, we'll predict the wins above replacement (WAR) a player will generate next season. We'll first download baseball season data using pybaseball and clean it. We'll do feature selection using a sequential feature selector to identify the most promising predictors for machine learning. We'll then train a ridge regression model to predict future season WAR. We'll measure error and improve the model.

WAR is a statistic that measures a player's value that compares them to an average replacement level player. The higher the WAR, the more valuable the baseball player.

**Project Steps**

- Download baseball season data
- Clean the data and prepare it for ML
- Run feature selection
- Create a machine learning model and estimate accuracy
- Improve accuracy
