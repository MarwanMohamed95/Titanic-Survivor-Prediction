
# Predicting Titanic Survived Passengers

In this project we try to predict the survived passengers in the Titanic dataset 
using different classification algorithms and choose the best one based on the accuracy result.

This project is binary classification problem, where the passenger either survived (1) or died (0). Here is a list of the columns of the dataset:

## Description
The sinking of the RMS Titanic is one of the most infamous shipwrecks in history. On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew. This sensational tragedy shocked the international community and led to better safety regulations for ships.

One of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew. Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others, such as women, children, and the upper-class.

In this challenge, we ask you to complete the analysis of what sorts of people were likely to survive. In particular, we ask you to apply the tools of machine learning to predict which passengers survived the tragedy.
## Evaluation

The historical data has been split into two groups, a 'training set' and a 'test set'. For the training set, we provide the outcome ( 'ground truth' ) for each passenger. You will use this set to build your model to generate predictions for the test set.

For each passenger in the test set, you must predict whether or not they survived the sinking ( 0 for deceased, 1 for survived ). Your score is the percentage of passengers you correctly predict.

The Kaggle leaderboard has a public and private component. 50% of your predictions for the test set have been randomly assigned to the public leaderboard ( the same 50% for all users ). Your score on this public portion is what will appear on the leaderboard. At the end of the contest, we will reveal your score on the private 50% of the data, which will determine the final winner. This method prevents users from 'overfitting' to the leaderboard.
## Features

- `PassengerID` - Unique ID for each column
- `Survived` - Whether the passenger survived (1) or not (0)
- `Pclass` - Class of the passenger's ticket. Either 1, 2 or 3.
- `Sex` - Passenger's sex (male or female)
- `Age` - Passenger's age
- `Sibsp` - Number of sibling or spouses aboard the Titanic
- `Parch` - Number of parents or children aboard the Titanic
- `Ticket` - Passenger's ticket number
- `Fare` - The price paid for the passenger's ticket
- `Cabin` - Passenger's cabin number
- `Embarked` - Port where the passenger embarked. Can be:
    - `C` - Cherbourg
    - `Q` - Queenstown
    - `S` - Southampton




## Objective

Predict which passenger survived the Titanic.



## Agenda of the notebook

### 1. Importing required libraries 
### 2. Acquiring the data
### 3. Exaploratory Data Analysis
### 4. Wrangling and Preprocessing the data
### 5. Modeling and predicting the output