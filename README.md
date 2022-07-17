# Ultimate Pokemon Battle

## Introduction:-

Pokemon is a universally well-known series which was originally created by “Satoshi Tajiri”,” Ken Sugimori ” and “Junichi Masuda” whereas it is watched by youngsters and grown-ups as well, it has a lot of fan following all over the world. It has a diverse set of creatures called as Pokemons with different characteristics, size, shape and abilities and the humans shown in this series are trainers who catch these creatures and train them to battle against each other.
In this project, we try to predict which battle style is more likely to win. The data provided will determine the win and lose percentage of a certain Pokemon with respect to their abilities, attack and defense, speed & HP, used during battles.

## Dataset-

Either we can read the dataset provided on Kaggle-"https://www.kaggle.com/terminus7/pokemon-challenge/" or just download it from kaggle only, under pokemons and combat domains. The pokemon set consist of characteristics and abilities of different pokemons while combat set consist of winners of the battle between two pokemons.

## Modelling-

We first described our data, drop any NULL values, merge our datasets to form columns such as total fights and win percentage and plotted different countplots.
Then we fit our input values, after splitting into train set and test set, into 4 different models namely LinearRegression, SVM, DecisionTreeRegressor & RandomForestRegressor. We then calculated the accuracy score and mean absolute error for each model and stored it in the list. We also calculated accuracies based on abilities such as Sp. def & def, Sp. att & att, HP & Speed, and variopus such pair of abilities. Then we listed the Percentage of Accuracy for each model based on the dataset. RandomForestRegressor model came out to be best fit model wrt accuracy score, LinearRegression model works best for attack based accuracies and so on.


