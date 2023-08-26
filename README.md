# Data-pre_processing-using-a-pipeline
# Automating the pre-processing of raw data with PIPELINES
During this project we shall look at the possible ways of processing raw data with a function and a pipeline.

Below are the tasks that we shall automate either through a function or pipeline

* Checking for missing numerical values and imputing them based on a given strategy

* Checking for missing categorical values and imputing them based on a given strategy 

* Harmonizing the scale of the numerical values through standard scaling

* Handling the categorical values with OneHot and Ordinal encoders 

Note : we should confirm that all the features are of the right data types 

### Steps to build a pre-processing pipeline

* reading the csv file and dropping the irrelevant features
* defining the columns that will used for our column transformer (Numerical and categorical Imputer)

#### Building a Numerical Imputer Transformer

#### Building a Categorical Imputer Transformer

#### Construct a Imputer Column Transformer (for both numerical and categorical features at once)

#### Since the output from the column transform is in an array form, we need to convert it back to a DataFrame 

#### Building a pipeline that imputes missing values and converts the results to a dataframe

#### Building a Modified StandardScale Transformer

#### Building a pipeline that imputes missing values, converts the results to a dataframe and scales the numerical features

#### Building a Modified OneHot encoder Transformer

#### Building a  pipeline that imputes missing values, converts the results to a dataframe,scales the numerical features and applied OneHot Encoder

#### Building a Modified Ordinal encoder Transformer

#### Building a pipeline that imputes missing values, converts the results to a dataframe,scales the numerical features,applied OneHot Encoder and ordinal encoder

This will leading us to the final pipeline that takes in the raw data and perform the above pre-processing at once.
  
