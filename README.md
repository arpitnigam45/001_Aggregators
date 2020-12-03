# 001_Aggregators
Data Analytics project repository

## About The Project
Poverty is an important indicator of economic well-being. Local and State policymakers use data on poverty levels to determine current economic conditions and variations based on demography of different regions. Poverty rates can be estimated  as percentages or categorized into various degrees.  Three models targeting point estimation, multiple classification and binary classification are put forward and compared.  

### Dependencies

 `Python 3.7.6`
 ```
pandas
numpy
matplotlib
seaborn
sklearn
scipy
statsmodels
```
### Build with

The project was built using `Jupyter Notebook` hence the code is in ipynb format.

1. Installation:
  ```
  pip install ipynb
```

2. Importing a Notebook
  for a file named test.ipynb;
```
import ipynb.fs.full.test
```
If you have access to Jupyter Notebook simply download the add link to clone file and opening it in Jupyter Notebook.

### File description

Data preprocessing.ipynb: cleans and preprocesses the original dataset. optionally export the dataset to a csv file.
Data Visualisation.ipynb: contains the code for basic data visualisation of some important features of the dataset.  
acs-2018-mlr.ipynb: this file contains the code for building and summarizing the multiple linear regression model.
acs-2018-classification.ipynb: summarizes the three classification models(random forest, logit regression and SVM).

### Usage

```pip install the required libraries and configure the directory for the csv files while importing them into the dataframe.```
