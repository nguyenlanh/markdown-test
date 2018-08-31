# PAYTV Churn Prediction Project   

## Overview
The objective of the churn prediction model is to predict the customers that are likely to stop using PayTV service hrough the usage behavior.

## Data Available
Data preparation for churn prediction starts with aggregating all available information about the customer. 
The data that is obtained for predicting the churn is classified in the following categories:

* **Transaction and billing data** such as the kind of services that are subscribed and average monthly bills.
* **Demographic data** such as gender, education, and marital status.
* **Behavior data** such as complaints data and price plan migration data.
* **Usage data** such as the number of calls and the number of text messages sent.
 
 
## Project structure
```
+-paytv-churn-prediction/
  +-__init__.py
  +-member-folder/
  | +-__init__.py
  | +-hieunt124/
  | +-lanhnv3/
  | | +-
  +-production/
    +-__init__.py
    +-conf/
    | +-__init__.py
    | +-main_conf.py
    | +-utils_conf.py
    +-service/
    | +-data/
    | | +-__init__.py
    | | +-gen_contract.py
    | | +-gen_internet.py
    | | +-gen_status_frequency.py
    | +-main/
    | | +-__init__.py
    | | +-building_features.py
    | | +-....

```


Folders:

* **data** - this folder contains CSV file with customers' info. It is a copy of data from ZhouFang928's example.
* **export** - this folder is for saving computing results (currently final model is stored there)
* **R** - master scripts
* **packages**
    * **externalpackages** - dummy package to maintain 3rd party packages dependencies 
    * **modelbuilder** - package that delivers funciton that builds GBM models 



## References

## Authors
