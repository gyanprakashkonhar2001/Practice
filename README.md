# Median housing value prediction

The housing data can be downloaded from https://raw.githubusercontent.com/ageron/handson-ml/master/. The script has codes to download the data. We have modelled the median house value on given housing data. 

The following techniques have been used: 

 - Linear regression
 - Decision Tree
 - Random Forest

## Steps performed
 - We prepare and clean the data. We check and impute for missing values.
 - Features are generated and the variables are checked for correlation.
 - Multiple sampling techinuqies are evaluated. The data set is split into train and test.
 - All the above said modelling techniques are tried and evaluated. The final metric used to evaluate is mean squared error.


## To run and create environment from env.yml file
```python
 conda env create --file env.yml
```

## To check the environments present in your Anaconda/miniconda
```python
conda env list
```
 - you can find a new environment named "mle-dev"

## To activate the mentioned envionment
```python
conda activate mle-dev
```

## To excute the script
```python
python nonstandardcode.py
```

'''sudo apt update'''