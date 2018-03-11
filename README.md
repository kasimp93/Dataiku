# Dataiku

The file us_census_dataiku.ipynb contains the code and analysis of the data set


Dataiku Interview Exercise

The following link lets you download an archive containing an “exercise” US Census dataset: http://thomasdata.s3.amazonaws.com/ds/us_census_full.zip

This US Census dataset contains detailed but anonymized information for approximately 300,000 people. 
The archive contains 3 files: 
o A large learning .csv file
o Another test .csv file

o A metadata file describing the columns of the two above mentioned files (identical for both) 
The goal of this exercise is to model the information contained in the last column (42nd), i.e., which people make more or less than $50,000 / year, from the information contained in the other columns. The exercise here consists of modeling a binary variable. 

Work with R or Python to carry out the following steps:
o Import the learning and text files
o Based on the learning file: 
o Make a quick statistic based and univariate audit of the different columns’ content and produce the results in visual / graphic format. 
This audit should describe the variable distribution, the % of missing values, the extreme values, and so on.

o Create a model using these variables (you can use whichever variables you want, or even create you own; for example, you could find the ratio or relationship between different variables, the one-hot encoding of “categorical” variables, etc.) to model wining more or less than $50,000 / year. Here, the idea would be for you to test one or two algorithms, such as logistic regression, or a decision tree. Feel free to choose others if wish.

o Choose the model that appears to have the highest performance based on a comparison between reality (the 42nd variable) and the model’s prediction. 

o Apply your model to the test file and measure it’s real performance on it (same method as above). 
The goal of this exercise is not to create the best or the purest model, but rather to describe the steps you took to accomplish it. 
Explain areas that may have been the most challenging for you. 

Find clear insights on the profiles of the people that make more than $50,000 / year. For example, which variables seem to be the most correlated with this phenomenon 
