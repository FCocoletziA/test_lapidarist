# README

This is a repository for sharing my solution to Intelimétrica's Data Science test. The time used for cracking the problem was about 5 hours.

The language used for solving the problem is `python`. The libraries used for the test are
- numpy
- pandas
- os
- seaborn
- plotly
- zipfile
- statsmodels

## Code
The three jupyter notebooks contain all the code and comments about the process. The numbering reflects the ordering of the tasks. Running the code will create new folders and files. (Please consider that Plotly graphs are not visible on Github). 

## Data
The databases are
- diamonds.zip: Features and prices of tens of thousands of diamonds
- Gringotts_diamonds.csv: Features of the stolen diamonds

## Results
The main results are given in the file *Results_linear_regression.csv*. The *obs_ci_lower* and *obs_ci_upper* columns represent 95% prediction inteervals for the diamond values. The *mean_ci_lower*, *mean_ci_upper* columns represent 95% prediction intervals for the conditional mean price of the diamonds.

The *Results_manual_solution.csv* file is given just for completeness, since the aforementioned solution is considered superior.

## Presentation
The *Client presentation.pdf* file contains a basic presentation of the methods and results for the client, who is supposed to know very little about the theme. The *Speaker notes - client presentation.pdf* contains the basic topics for each slide, since they are mostly visual.

## Technical comments
Most of the coments are made in the code, but here is a high level discussion about the methods that were considered , but not implemented, and a little interpretation of the main findings.
