# All About Seattle & St Louis Rainfall
for data2320: explore and compare how much it rains in Seattle and St. Louis
  
  
    - links to the data: https://www.ncei.noaa.gov/cdo-web/search?datasetid=GHCND


Data Preparation:
    - To clean up the data (data_preparation.ipynb):
      ~ converted necessary data types
      ~ narrowed st louis data to just 2018-2022 and one weather station
      ~ replace seattle's missing values with the mean across years of values on that day
      ~ narrow to a data frame with precipitation data 2018-2022 for st louis and seattle: clean_seattle_stlouis_weather.csv


*
*
*
*
*

Some notes:

Convert the domain problem into a data problem
  ~ we want to describe the data (rather than predict)
  
 Engage with Ethical Considerations
  ~ Are we: moving toward equitable outcomes, respecting privacy and consent, avoiding bias in data sources, avoiding bias in algorithms and analysis?
  
 Also consider these
  ~
