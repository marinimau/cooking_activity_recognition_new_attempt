# Cooking activity recognition based on indoor air-quality sensors.

The application classifies the minutes in which the user has cooked. The dataset contains one record per minute for approximately one month.
This is the the same problem of my bachelor's degree thesis but dealt with different techniques.

*we consider "cook", for example, also heat the milk in the microwave*

## Preprocessing:

* Principal Component Analysis
* Outliers removing
* Balance dataset

## Classification:

* Multi-layer Perceptron classifier
* 70-30% train/test split

## Score:

* Recall: >80%
* Precision: >80%
* F1: >80%

*consider 5-minutes granularity in annotation phase*
