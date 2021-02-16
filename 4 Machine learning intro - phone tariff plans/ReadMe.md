# Machine learning intro - phone tariff plans

We are back to analysing data of most popular tariffs (see project #2).
But now we are building recommendation system of most suitable tarif, so a machine learning categorization algorithm.

## Task debrief
1. We use exactly the same preporcessed data from previous telecom project
1. Our recomendation system should provide accuracy score at least 0.75

## Project flow
_Data preparation:_
1. Splitting data to training, validation and test sets.

_Modeling:_
1. Creating three real categorization models:
- logistic;
- decision tree;
- random forest;
1. Building a manual loop to understand iteratively best hyperparameters
1. Building one dummy model and random model for reasonable-ness check

## Some results
1. Random forest model works best out of three real models with defined hyperparameters, so reaching target accuracy score of 0.75
1. Random forest model here works better than dummy model or naive random model.
