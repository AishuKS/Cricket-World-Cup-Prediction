# Predictions for the 2023 ICC Cricket World Cup

## Authors
- **Aishwarya Kandasamy**, Data Science, Illinois Institute of Technology, Chicago, USA  
  *Email: akandasamy@hawk.iit.edu*
- **Deepika Alagiriswamy Panneerselvam**, Data Science, Illinois Institute of Technology, Chicago, USA  
  *Email: dalagiriswamypanneer@hawk.iit.edu*

## Course Information
**Course:** CSP571-Data Preparation and Analysis  
**Professor:** Jawahar Panchal

## Table of Contents
1. [Abstract](#abstract)
2. [Introduction](#introduction)
3. [Proposed Methodology](#proposed-methodology)
4. [Problem Statement](#problem-statement)
5. [Data Summary](#data-summary)
6. [Analysis](#analysis)
7. [Modeling](#modeling)
8. [Conclusion](#conclusion)
9. [References](#references)

## Abstract
Using a machine learning technique, the Random Forest algorithm predicts the winner of the 2023 Cricket World Cup based on a variety of historical and contemporary cricket data parameters, including team performance, player statistics, pitch conditions, and more. The Random Forest algorithm makes predictions about who will win the tournament based on these variables. By combining several decision trees, this technique improves prediction accuracy and, in the end, assists analysts and cricket fans in making well-informed projections regarding the probable winner of the 2023 Cricket World Cup.

**Keywords:** Cricket, Random Forest models, predictions, fixtures

## Introduction
The 2023 Cricket World Cup will take place in India, with play starting on October 5 and ending on November 19. In this four-year One Day International (ODI) cricket competition, eleven national teams from Afghanistan, Australia, Bangladesh, England, India, the Netherlands, New Zealand, Pakistan, South Africa, and Sri Lanka are playing. India serves as the tournament's host nation.

## Proposed Methodology
For this project, four datasets were gathered from HowStats.com. The Random Forest algorithm was chosen due to its strength and accuracy in handling categorical data. The methodology involves:

1. Compiling information from multiple sources
2. Data cleaning for uniformity
3. Model construction: choosing the appropriate algorithm
4. Extracting knowledge from the output of the model
5. Graphical representation of the results
6. Concluding the winner of the prediction

## Problem Statement
This project aims to:
- Predict the winner of the competition with high accuracy using historical and current data.
- Evaluate different cricket-related data, such as individual and team statistics.
- Identify and assess the most important factors influencing a team's chances of winning.
- Forecast each match's outcome for the duration of the competition.
- Run mock matches for upcoming contests, including the semifinals and championship.

## Data Summary
### Description
The data is gathered from HowStat.com, which has ODI match results going back to the World Cup in 2015. Data from Cricbuzz is also included.

### Datasets
- `world_cup_2023.csv`: Includes winning percentage, total number of wins and losses in World Cup matches, and loss percentage.
- `results.csv`: Contains games played in 2015, along with the ground played and margin.
- `fixtures.csv`: Contains the schedule for every match in the tournament.
- `icc_ranking.csv`: Lists the ICC rankings of the competing teams.

## Analysis
### Exploratory Data Analysis
Graphs representing the win percentage in ODIs by each team and ICC ODI ratings highlight overall team performance and trends over time.

### Train Test Set
The dataset was split into 80% training and 20% testing sets to train the models and measure their accuracy.

## Modeling
### Random Forest
The Random Forest model achieved an accuracy of 63% for training data and 53% for testing data. The model handles categorical data well and compares the winning percentage of each team against others.

### Confusion Matrix
The confusion matrix evaluates the performance of the Random Forest algorithm in classifying instances (predicting whether a team will win, lose, or draw).

### Feature Engineering
Feature engineering involved modifying or adding new, meaningful features to the dataset to improve the performance of the machine learning models.

## Conclusion
The project successfully extracted numerous insights and examined the ICC cricket dataset. The Random Forest model demonstrated an accuracy of 63% on the training set and 53% on the test set, making it a reliable method for predicting cricket match outcomes.

## References
1. Abdul Basit, Muhammad Bux Alvi, Fawwad Hassan Jaskani, Majdah Alvi, Kashif H. Memon, Rehan Ali Shah. “ICC T20 Cricket World Cup 2020 Winner Prediction Using Machine Learning Techniques”, 2020 IEEE 23rd International Multitopic Conference (INMIC), Bahawalpur, Pakistan, 2021.
2. Nigel Rodrigues, Nelson Sequeira, Stephen Rodrigues, Varsha Shrivastava, “Cricket Squad Analysis Using Multiple Random Forest Regression”, IEEE, Chikmagalur, India, 2019.
3. Predictive Analysis of Matches in the 2023 Cricket World Cup Using Python and Data Science, [Link](https://medium.com/@dotunomoboye/predictive-analysis-of-indias-victory-in-the-2023-cricket-world-cup-using-python-and-data-science-d00083286a08)
