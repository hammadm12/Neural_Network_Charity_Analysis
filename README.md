# Neural Network Charity Analysis

## Overview

For this project, we are to utilize the deep-learning neural networks in the Tensorflow program in Python to analyze the success of charitable donations. Through this analysis, we hope to help the organization predict where to make their investments. In order to succesfully make use of the deep-learning neural networks, we are going to the preprocess the data for the model, and then compile, train and avluate the model.

## Results

During the data reprocessing step, we removed the EIN and NAME identification columns since the primary column for our model will be the "IS_SUCCESSFUL' column due to the column contains data whether or not the charity donation was sufficiently used. 

The following columns were considered to be the features of the model:
- AFFILIATION — listed as "Affiliated sector of industry"
- CLASSIFICATION — listed as "Government organization classification"
- USE_CASE — listed as "Use case for funding"
- ORGANIZATION — listed as "Organization type"
- STATUS — listed as "Active status"
- INCOME_AMT — listed as "Income classification"
- SPECIAL_CONSIDERATIONS — listed as "Special consideration for application"
- ASK_AMT — listed as "Funding amount requested" 

