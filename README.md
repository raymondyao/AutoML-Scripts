# AutoML-Scripts
The repository contains the example notebooks and datasets for AutoML.

## Require

HANA instance with PAL installed. https://www.sap.com/sea/products/technology-platform/hana.html

Python Client installation: pip install hana-ml

## File descriptions

data loader.ipynb: scripts to read csv in the folder and pickle the pandas dataframe

hana test.ipynb: scripts to upload pandas dataframe to HANA instance and execute AutoML experiments

classification_dat.pkl: the pickled pandas dataframe for classification datasets

regression_dat.pkl: the pickled pandas dataframe for regression datasets
