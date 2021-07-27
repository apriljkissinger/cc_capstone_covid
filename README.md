# cc_capstone_covid
Codecademy Capstone Project. A set of regression models to predict the percentage of the population in US counties that tested positive for Covid. 
And a set of classification models to predict the state and region of a US county based on the percentage of Covid cases and mask use frequency.


This notebook was built for the Codeacademy Data Science Certification Capstone Project. I have chosen to build two sets of models, a set of regressions and a 
set of classifications. The regression models will predict how poverty percentage, population density, median household income, and frequency of mask usage across 
US counties affected the number of Covid-19 cases. The classification models will use the percent cases and mask use frequencies of a county to predict its US 
state and economic region.

All models will use a dataset of aggregated COVID-19 cases built by The New York Times and a mask survey dataset built by the New York Times and Dynata. The 
regression models will in addition use a census of US poverty by the USDA Economic Research Services and a land census by the United States Census Bureau.  

Please refer to the references below for the links to the data:  
1). NY Times and Dynata data:  
    a. US counties data: us-counties.csv  (The New York Times, 2021)  
    b. Mask use data: mask-use > mask_use_by_county.csv (The New York Times and Dynata, 2021)   
2). The United States Census Bureau Data:   
    a. Land Area > LND01.xls  (United States Census Bureau, 2011)  
3). The USDA Economic Research Services Data:  
    a. Poverty and Income data: Poverty estimates for the U.S., States, and counties, 2019  (USDA: Economic Research Service, 2019)  

The New York Times and Dynata mask data was collected from 250,000 online surveys done between 07/02/20-07/14/20.  I am unsure under what website or 
group of websites this data was collected, but in general survey data tends to be biased as it is up to the websites that give or advertise the survey and those 
who are willing to take it.


If you have any questions, comments, or concerns, or would just like to chat, please reach out: apriljkissinger@gmail.com


References
Bureau of Economic Analysis. (2021). Regional Economic Accounts. Retrieved July 12, 2021, from https://apps.bea.gov/iTable/definitions.cfm?did=243&reqId=70

Plotly. (2015). geojson-counties-fips. Retrieved July 21, 2021 from https://github.com/plotly/datasets/blob/master/geojson-counties-fips.json

The New York Times. (2021). Coronavirus (Covid-19) Data in the United States. Retrieved July 09, 2021, from https://github.com/nytimes/covid-19-data/tree/master/mask-use

The New York Times and Dynata. (2021). Estimates from The New York Times, based on roughly 250,000 interviews conducted by Dynata from July 2 to July 14. Retrieved July 09, 2021, from https://github.com/nytimes/covid-19-data

USDA: Economic Research Service. (2019). Poverty estimated for the U.S., States, and counties, 2019. Retrieved July 09, 2021, from https://www.ers.usda.gov/data-products/county-level-data-sets/download-data/

United States Census Bureau. (2011). Land Area. Retrieved July 18, 2021 from https://www.census.gov/library/publications/2011/compendia/usa-counties-2011.html#POP
