# Research analysis - apartment prices

In this project we define metrics that influence the apartments prices most.
We mainly use visualization tools and correlation analysis to figure out influencing features.

## Task debrief
1. Final task is to understand what is the market price of the lot.
1. In this project we don't aim to forecast prices, but rather uncover most important factors and relations.
1. We are provided with real estate sales data in Sain Petersburg and suburb for couple of years, e.g.:
 - number of flors in the building;
 - living area;
 - distance to city center;
 - etc.

## Project flow
_Preprocessing:_
1. deleting duplicates;
1. filling in missing values, using medians;
1. lemmatizing diffirent ways to name same geographical area to lemmas;
1. deleting unreasonable values (like to high ceiling, or kitchen area > total area).

_Preliminary calculations:_
1. calculating price per meter;
1. defining group of appartment (top floor, first floor, middle floors);

_Research analysis_:
1. Analysing long tail with box-plot;
1. Building histogramms for the features to assess data from helicopter view;
1. Defining interdependencies with matplotlib:
- how price depends on km till city center;
- how price depends on date of publishing;
- how price depends on the number of rooms/area;
- etc.

## Some results:
1. City center has almost no economy objects;
1. The greater the total aread the less is the price per sq.meter;
1. Geographical center is area within 7km zone of the center, after that threshold price substantially declines;
1. The longer the object is published the less is the price of the object;
1. etc.
