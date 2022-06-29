# DATA informs

All data displayed here were obtained from the repository: COVID-19 Data Repository by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University

- Link to the repository: [https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_time_series](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_time_series) 

to update the charts, just download the datasets files again in their original repository following the standard protocol: 

for the cases file:

> click `time_series_covid19_confirmed_global.csv` then `View raw` then `Ctrl + S` and save the folder in the rite directory of your computer. 

for the deaths file: 

> click `time_series_covid19_deaths_global.csv` then `View raw` then `Ctrl + S` and save the folder in the rite directory of your computer. 

Then you should run the python file `convert-to-json` displayed in this folder to reorganize and convert the `.csv` files for the charts creation. 

ps.: After converting to .json it is recommended that you delete the .csv files to avoid verification problems when generating graphics.