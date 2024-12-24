# ILP_score_prediction
The IPL Score Prediction Project focuses on analyzing and predicting scores in the IPL (Indian Premier League) T-20 matches. This project involves data collected between 2008 and 2020, covering various details such as venues, teams, runs, and wickets. The objective is to predict scores based on past matches and assess how closely the predicted scores match the actual ones. The process utilizes regression techniques to estimate unknown values by leveraging known data from similar instances.
 
Purpose of the Study 
The goal of this project is to predict scores using historical data and evaluate which algorithm performs the best. The machine learning model assigns rating points to players based on their statistics. These ratings are then used to determine the winner between two teams. At the final stage, the algorithm predicts the champion from the top two teams.

Data Sources 
The dataset used for IPL score prediction comprises 12 years of match data. It includes information about runs, venues, batsmen, teams, and wickets, among other details.
 
 
 #### Dataset Description
 
 Contains  rows 76014 and 8 columns 
 
• mid: Unique match id.

• date: Date on which the match was played.

• venue: Stadium where match was played.

• battingteam: Batting team name.

• bowlingteam: Bowling team name.

• batsman: Batsman who faced that particular ball.

• bowler: Bowler who bowled that particular ball.

• runs: Runs scored by team till that point of instance.

• wickets: Number of Wickets fallen of the team till that point of instance.

• overs: Number of Overs bowled till that point of instance.

• runslast5: Runs scored in previous 5 overs.

• wicketslast5: Number of Wickets that fell in previous 5 overs.

• striker: max(runs scored by striker, runs scored by non-striker).

• non-striker: min(runs scored by striker, runs scored by non-striker).

• total: Total runs scored by batting team at the end of first innings.

## Algorithms Used
- The project utilizes the following machine learning algorithms for score prediction:

*Decision Tree Regressor*
*Linear Regression*
*Random Forest Regression*
*Lasso Regression*
*Support Vector Machine Regression*
*Neural Network Regression*
