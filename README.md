# Regression-HousePricePrediction

<br />
<p align="center">
  <a href="https://github.com/thenomaniqbal/">
    <img src="images/profile.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Boston House Price Prediction</h3>


## 📝 Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Contributers](#contributers)
* [Contact](#contact)


<!-- ABOUT THE PROJECT -->
## Project

Boston housing price prediction using Regression Algorithms  

<img src="https://raw.githubusercontent.com/thenomaniqbal/boston-housing-price-prediction/master/ln.png" width="100%">

1. CRIM per capital crime rate by town  
2. ZN proportion of residential land zoned for lots over 25,000 sq.ft.  
3. INDUS proportion of non-retail business acres per town  
4. CHAS Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)  
5. NOX nitric oxides concentration (parts per 10 million)  
6. RM average number of rooms per dwelling  
7. AGE proportion of owner-occupied units built prior to 1940  
8. DIS weighted distances to five Boston employment centers  
9. RAD index of accessibility to radial highways  
10.TAX full-value property-tax rate per 10,000 USD  
11. PTRATIO pupil-teacher ratio by town  
12. Black 1000(Bk — 0.63)² where Bk is the proportion of blacks by town  
13. LSTAT % lower status of the population  

The visualization of the data set is implemented in a separate file: <a href="[https://github.com/thenomaniqbal/HousePricePrediction](https://github.com/thenomaniqbal/HousePricePrediction/blob/master/Visualization.ipynb)">Visualization</a> 

<a href="https://github.com/thenomaniqbal/boston-housing-price-prediction/">
  <img src="https://raw.githubusercontent.com/thenomaniqbal/boston-housing-price-prediction/master/plots/predictions_vs_ytest.png" width="100%">

  <img src="https://raw.githubusercontent.com/thenomaniqbal/boston-housing-price-prediction/master/plots/model_mse_scores.png" width="100%">

  <img src="https://raw.githubusercontent.com/thenomaniqbal/boston-housing-price-prediction/master/plots/feature_importance.png" width="100%">

  <img src="https://raw.githubusercontent.com/thenomaniqbal/boston-housing-price-prediction/master/plots/pairplot.png" width="100%">
 </a>

`thenomaniqbal`, `boston-housing-price-prediction`,  `thenomaniqbal@gmail.com`


### Built With

* [Python](python)
* [Flask](flask)




<!-- GETTING STARTED -->
## Getting Started

Clone the repo and extract it ....

### Prerequisites

This is the list of things you need to use the software and how to install them.
* Python
```
Version python 3.8 <
```
* Pandas
* sklearn
* gunicorn
* scipy
* numpy
* matplotlib
* flask


```

3. Required Imports:
```
import numpy as np
import pandas as pd
import matplolib.pyplot as plt
from flask import Flask,request, url_for, redirect, render_template
import pickle
```





## References
* Stackoverflow
* flask
