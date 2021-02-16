# Machine learning part 1 - bank clients categorisation

In this project we continue with machine learning categorisation task.
We as analytics of commercial bank need to build most accurate model that will say if you can expect a client to leave a bank or not.

## Task debrief
1. Based on historical data we forecast consumer willingnes to leave.
1. We have to build a model that will reach F1 score of at least 0.59

## Project flow
_Data preparation:_
1. Performing `one hot encoding` and `ordinal encoding`
1. Performing data `split`
1. `Scaling data`

_Research analysis:_
1. Assessing the portrait of the consumer who left and who stays

_Modeling:_
1. Building `decision tree` on `unbalanced classess` while optimizing for F-1 or Accuracy
1. Same set up and optimization of hyperparameters for `random forest`
1. Assessing how main metrics (`precision`, `recall`, `auc-roc`, etc.) changed with the change of hyperparameters
1. Performing `upsampling`, `downsampling` and classification threshold

## Some results
1. We reach desired level of `F1-score` given 20 estimators and depth of 8 for random forest. We also had to perform upsampling to reach targeted measure.

