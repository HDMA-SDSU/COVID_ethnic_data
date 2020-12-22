Python script: UpdateEthnicityPlot.ipynb 

This script takes SD_Ethnicity-COVID-Cases_Cumulated.csv as input, grabs the current date's accumulated infected cases 
of different ethnic groups from the county website and add them to the csv file, and finally plot the daily infected cases.

Python script: UpdateEthnicityPlot_Hospitalization.ipynb 

This script takes SD_Ethnicity-COVID-Hospital_Cumulated.csv as input, grabs the current date's accumulated hospitalization cases 
of different ethnic groups from the county website and add them to the csv file, and finally plot the daily hospitalization cases.

This script can be converted to .py and ran on a server on a daily basis. But may need to add some python pakages and update the path in the script before running it.


There are no data on those dates, averaged value of the day before that data and after that date is used:
11/10/2020
11/25/2020
11/28/20
11/30/20
12/15/20

Please check the data before using because sometimes the county will miss data someday. 
