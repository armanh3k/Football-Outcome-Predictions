# Football-Outcome-Predictions

> A thorough investigation into the world of Football using Data Science. This project uses Machine Learning and other Data Science techniques for the aim of accurately predicting the outcome of football matches from the biggest leagues in the world. Models are created based on match results since 1990 and will be used to predict the outcome of future matches.

Packages used in this project include: pandas, seaborn, sk-learn and more.

## Milestone 1: EDA and Data Cleaning
The use of pandas and data visualisation libraries such as seaborn can quickly give great insight into data being investigated... From given features in data, new features can be theorised and brainstormed for implementation during Feature Engineering stage...

Check for null values...

Examples of plots used to get insight (data visualisation)... h



## Milestone 2: Feature Engineering

Feature Engineering is the process of creating new relevant features from raw data to improve the accuracy of models. Having many different features to select from during model training can assist in finding the hidden patterns which heavily influence the model performance.
From the EDA and Data Cleaning section, potential features which can have impact on the final result were brainstormed. Features I created include:
-  Elo rating of Home and Away team going into a match (supplied from an external pickle file)
- Number of points of Home and Away team
- Current position of Home and Away team
- Total goals scored by Home and Away Team 
- Number of wins/draws/losses for Home and Away team
- Win streak of Home and Away team
- and many more!

A pipeline was created to create all the features for each league table supplied already. The pipeline is created assuming the user has downloaded given football dataset to their local directory. The format of the football dataset is shown below:

| Home_Team      | Away_Team   | Result | Link                                                                      | Season | Round | League         |
|----------------|-------------|--------|---------------------------------------------------------------------------|--------|-------|----------------|
| Fulham         | Arsenal     | 0-3    | https://www.besoccer.com/match/fulham/arsenal/202172184                   | 2021   | 1     | premier_league |
| Crystal Palace | Southampton | 1-0    | https://www.besoccer.com/match/crystal-palace-fc/southampton-fc/202172183 | 2021   | 1     | premier_league |

## Upload Data

## Model Training

## Inference
