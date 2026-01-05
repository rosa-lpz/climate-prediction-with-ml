# Climate Prediction with Machine Learning

Capstone project for [Machine Learning Zoomcamp by DataTalksClub](https://github.com/DataTalksClub/machine-learning-zoomcamp).


## Dataset
National Centers for Environmental Information (NOAA) 
* https://www.ncei.noaa.gov/cdo-web/search?datasetid=GHCND

### Parameters
WT03 - Thunder
WT04 - Ice pellets, sleet, snow pellets, or small hail"
PRCP - Precipitation
WT05 - Hail (may include small hail)
WT06 - Glaze or rime
WT07 - Dust, volcanic ash, blowing dust, blowing sand, or blowing obstruction
WT08 - Smoke or haze
SNWD - Snow depth
WT09 - Blowing or drifting snow
WDF1 - Direction of fastest 1-minute wind
WDF2 - Direction of fastest 2-minute wind
WDF5 - Direction of fastest 5-second wind
WT10 - Tornado, waterspout, or funnel cloud"
PGTM - Peak gust time
WT11 - High or damaging winds
TMAX - Maximum temperature
WT13 - Mist
WSF2 - Fastest 2-minute wind speed
FMTM - Time of fastest mile or fastest 1-minute wind
ACMH - Average cloudiness midnight to midnight from manual observations
WSF5 - Fastest 5-second wind speed
SNOW - Snowfall
WDFG - Direction of peak wind gust
WT14 - Drizzle
ACSH - Average cloudiness sunrise to sunset from manual observations
WT16 - Rain (may include freezing rain, drizzle, and freezing drizzle)"
WT18 - Snow, snow pellets, snow grains, or ice crystals
WSF1 - Fastest 1-minute wind speed
AWND - Average wind speed
WT21 - Ground fog
WSFG - Peak gust wind speed
WT01 - Fog, ice fog, or freezing fog (may include heavy fog)
WESD - Water equivalent of snow on the ground
WT02 - Heavy fog or heaving freezing fog (not always distinguished from fog)
PSUN - Daily percent of possible sunshine for the period
TAVG - Average Temperature.
TMIN - Minimum temperature
TSUN - Total sunshine for the period 

## Linear Regression
Simple linear regression is a fundamental statistical method used to explore the relationship between two variables: one independent variable (predictor) and one dependent variable (outcome). The goal of simple linear regression is to model this relationship by fitting a straight line (the regression line) through the data points, which best represents the relationship between the variables.


## Logistic Regression

Logistic regression is a statistical method used to model the relationship between a set of independent variables and a binary dependent variable, where the outcome is typically coded as 0 or 1 (e.g., no/yes, false/true). Unlike linear regression, which predicts a continuous outcome, logistic regression predicts the probability of a particular class or event occurring.

The logistic regression model uses the logistic function to transform the linear combination of the independent variables into a probability that ranges between 0 and 1. This makes it particularly useful for classification problems, such as determining whether a customer will make a purchase, if a patient has a certain disease, or if a student will pass a course.

## Directory structure

The directory structure of your new project will look something like this (depending on the settings that you choose):

```
├── LICENSE            <- Open-source license if one is chosen
├── Makefile           <- Makefile with convenience commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- A default mkdocs project; see www.mkdocs.org for details
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── pyproject.toml     <- Project configuration file with package metadata for 
│                         {{ cookiecutter.module_name }} and configuration for tools like black
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── setup.cfg          <- Configuration file for flake8
│
└── {{ cookiecutter.module_name }}   <- Source code for use in this project.
    │
    ├── __init__.py             <- Makes {{ cookiecutter.module_name }} a Python module
    │
    ├── config.py               <- Store useful variables and configuration
    │
    ├── dataset.py              <- Scripts to download or generate data
    │
    ├── features.py             <- Code to create features for modeling
    │
    ├── modeling                
    │   ├── __init__.py 
    │   ├── predict.py          <- Code to run model inference with trained models          
    │   └── train.py            <- Code to train models
    │
    └── plots.py                <- Code to create visualizations   
```




# References

* Coursera - Predicting Extreme Climate Behavior with Machine Learning
