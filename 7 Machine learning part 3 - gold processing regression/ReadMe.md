# Machine learning part 3 - gold processing regression

Here we have to prepare a prototype machine learning model for Digits. 
The company develops solutions for the efficient operation of industrial enterprises.
The model should predict the recovery rate of gold from a gold-bearing ore. 

## Task debrief
1. We are provided with raw data from the gold processing sensors.
1. We have to check also that gold recovery is calculated in a correct way.
1. Model effectiveness in assessed based on `SMAPE` metric

## Project flow
_Pre-processing:_
1. Deleting NaN values
1. Deleting unnecessary values not influencing gold recovery

_Data preparation:_
1. Checking if the gold recovery in our formula matches the data from sensors and define reasons why difference may occure
1. `Splitting` data
1. `Scaling` data

_Modeling:_
1. Performing `GridSearchCV` on three types of regular models: `decison tree`, `random forest`, `linear regression`
1. Performing `Cross-validation` on manually built function for `SMAPE`

_Statistical analysis:_
1. `Testing hypothesis` that calculated effectiveness equals recovery effectiveness got from sensors.
1. `Testing hypothesis` that weight of material in different sets (train and test) is equal or not.

_Research analysis:_
1. Assessing how different elements concentration depend on the gold processing stage
1. Assessing outliers with `box-plot`

## Some results
1. Best draft model build on basis of `random forest` model that beats dummy model and other models
