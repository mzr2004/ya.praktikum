# Machine learning part 2 - oil wells regression and bootstrap

Now we work for the oil production company. We need to decide where to drill the new well.
We follow several steps to make our recos:
- In a selected region, characteristics for wells are collected: oil quality and volume of its reserves;
- Build a model to predict the volume of reserves in new wells;
- The wells with the highest value estimates are selected;
The region with the maximum total profit of the selected wells is determined.

## Task debrief
1. We have oil samples in three regions. The characteristics for each well in the region are already known.
1. We shall analyze the potential rewards and risks using the Bootstrap.

## Project flow
_Data preparation:_
1. Unnecessary data is deleted
1. Data is `splited to train and validation samples`
1. Data is `scaled`

_Modeling:_
1. Simple models are build for each potential region
1. Building function to determine `break even point` in each potential region
1. Performing `bootstrap` to select specific number of drills in each region and build distribution of profits and lossess in each region

## Some results
1. Based on comparison of profits and lossess we recommend region #3 for further exploration
