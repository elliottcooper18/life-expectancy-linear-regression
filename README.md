# Linear regression model to predict life expectancy

This is a simple model which I have developed in my quest to become omniscient in machine learning

## What is the model doing

The model is prediciting life expectancy based on years in education from countries about 180 countries around the world.

The dataframe is split into one in which the data is based only of that from 2015.

The dataframe is split into testing and trainig data on an approximate 60/40 split, which is what I found to give the lowest mean square error when playing
around with it.

The end result from this was getting to a MAE of: 3.6342687846127224

## Interesting points

The function `getxy(..)` 
