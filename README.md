# COVID-19-Worldwide-USA-Data-Analysis

<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
* [Libraries used](#libraries-used)
* [Dataset used](#dataset-used)
* [Built on](#built-on)
* [Questions answered](#questions-answered)
* [Model Training and Testing Steps](#model-training-and-testing-steps)
* [Ackowledgements](#ackowledgements)
* [Author](#author)


## About the Project 
Exploratory Data Analysis of COVID-19 dataset to understand the spread of cases worldwide as well as in the USA. </br></br>
The python notebook __"COVID-19 WORLDWIDE EDA"__ explores the current situation of the COVID-19 pandemic across the globe and then delves deeper into the current situation in the US to answer a few questions regarding the severity of spread between countries as well as between the states of the USA. 

It also looks into some metrics such as the death rate with respect to positive cases and rate of positive cases with respect to the number of tests. 

#### Since the graphs are implemented using plotly, they do not appear in the github preview. The notebook will need to be run using an environment like Jupyter notebook for the graphs to be visible.

## Libraries used 
* Pandas
* Numpy
* Matplotlib
* Seaborn
* plotly
* cufflinks

```bash
import pandas as pd
import plotly.graph_objs as go 
from plotly.offline import init_notebook_mode,iplot,plot
init_notebook_mode(connected=True) 
import matplotlib.pyplot as plt
%matplotlib inline
import seaborn as sns
import numpy as np

import cufflinks as cf
init_notebook_mode(connected=True)
# For offline use
cf.go_offline()
```

## Dataset used 
* __CSSEGIS__ - csse_covid_19_time_series.csv
* __covidtracking.com__ - current.csv

## Built with
* Jupyter Notebook

## Questions answered 
1. How are COVID-19 cases distributed worldwide?
2. How have cases increased with time in the most infected countries?
3. At what rate have cases increased daily in the most infected countries?
4. Which states in the US have the most and least positive cases?
5. Which states in the US have performed the highest and lowest number of tests?
6. Which states in the US show the highest positive case rate with respect to tests conducted?
7. Which states in the US show the highest death rate with respect to positive cases?

## Ackowledgements
* <a href='https://github.com/CSSEGISandData/COVID-19'>CSSEGIandData</a> - Global Dataset
* <a href='https://covidtracking.com'>covidtracking.com</a> - USA cases Dataset

## Author - Sharan Sukesh




