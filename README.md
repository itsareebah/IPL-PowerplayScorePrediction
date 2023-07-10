## IPL-Powerplay Score Prediction- IIT Madras Hackathon
PREDICTING IPL POWERPLAY SCORE USING ML ALGORITHMS

IPL is one of the most popular cricket leagues in the world. In this project, I have developed and deployed a Machine Learning model for predicting the powerplay scores of a particular innings of a particular match, using past history of ipl matches. Given some information about the match (like venue, batting and bowling teams, players who batted in powerplay, players who bowled in powerplay,etc) , the model can predict the number of runs scored by the batting team during the powerplay.

The dataset available contains ball-by-ball information and match information for the past 20 years, hence I have performed the required preprocessing to extract the exact variables that can be used by our model. Did some feature engineering to group similar players (K Means - clustering)

Different ML algorithms that were used and tested are Ridge Regression, GradientBoosting, Adaboost, VotingRegressor.

